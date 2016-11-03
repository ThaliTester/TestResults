#### Test 92249550c9056e1_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-04 00:12:18.953  4015  4282 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-04 00:12:19.025  4015  4282 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-04 00:12:19.424  5670  5670 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-04 00:12:19.430  5670  5670 D AndroidRuntime: CheckJNI is OFF
11-04 00:12:19.461  5670  5670 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-04 00:12:19.498  5670  5670 I Radio-JNI: register_android_hardware_Radio DONE
11-04 00:12:19.512  5670  5670 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-04 00:12:19.515   930  4043 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-04 00:12:19.535  5670  5670 D AndroidRuntime: Shutting down VM
11-04 00:12:19.543  3978  4006 W SearchService: Abort, client detached.
11-04 00:12:19.552  3978  4238 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@b66294d
11-04 00:12:19.552  3978  3978 I HotwordDetector: Closing mic
11-04 00:12:19.552  3978  4269 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-04 00:12:19.565   930  4041 I ActivityManager: Start proc 5679:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-04 00:12:19.628   514  4273 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-04 00:12:19.630   514  4273 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-04 00:12:19.634   514  4273 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-04 00:12:19.635   514  4273 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-04 00:12:19.635   514  3027 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-04 00:12:19.637  3978  4268 I MicroRecognitionRnrImpl: Detection finished
11-04 00:12:19.637  3978  4239 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-04 00:12:19.648  5679  5679 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-04 00:12:19.668  5679  5679 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-04 00:12:19.720  5679  5679 I LibraryLoader: Time to load native libraries: 49 ms (timestamps 8589-8638)
11-04 00:12:19.720  5679  5679 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 00:12:19.741  5679  5679 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {15a23b9}
11-04 00:12:19.741  5679  5679 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 00:12:19.742  5679  5679 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-04 00:12:19.745  5679  5679 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-04 00:12:19.746  5679  5679 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 00:12:19.779  5679  5679 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 00:12:19.787  5679  5679 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 00:12:19.787  5679  5679 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 00:12:19.787  5679  5679 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 00:12:19.787  5679  5679 I Adreno  : Build Date                       : 12/06/15
11-04 00:12:19.787  5679  5679 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 00:12:19.787  5679  5679 I Adreno  : Local Branch                     : mybranch17112971
11-04 00:12:19.787  5679  5679 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 00:12:19.787  5679  5679 I Adreno  : Remote Branch                    : NONE
11-04 00:12:19.787  5679  5679 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 00:12:19.817   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28b3ab7:true
,11-04 00:12:19.847   406   406 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[14249]" dev="sockfs" ino=14249 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 00:12:19.847   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14249]" dev="sockfs" ino=14249 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 00:12:19.859  5679  5679 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 00:12:19.867  5679  5679 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 00:12:19.891  5679  5717 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-04 00:12:19.887  3472  3472 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32383]" dev="sockfs" ino=32383 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 00:12:19.891  3472  3472 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32383]" dev="sockfs" ino=32383 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 00:12:19.891  3172  3172 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[21447]" dev="sockfs" ino=21447 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 00:12:19.891  3172  3172 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[21447]" dev="sockfs" ino=21447 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 00:12:19.895  5679  5704 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 00:12:19.927  5679  5717 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 00:12:20.001  3451  3451 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32388]" dev="sockfs" ino=32388 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 00:12:20.001  3451  3451 W Binder_7: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32388]" dev="sockfs" ino=32388 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 00:12:20.004  3449  3449 W Binder_5: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32387]" dev="sockfs" ino=32387 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 00:12:20.004  3449  3449 W Binder_5: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32387]" dev="sockfs" ino=32387 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 00:12:20.005   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +459ms
11-04 00:12:20.006  3675  3675 I Keyboard.Facilitator: onFinishInput()
,11-04 00:12:20.036  5679  5679 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5679
,11-04 00:12:20.122  5679  5679 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 00:12:20.271  5679  5720 D jxcore_app_log: JniHelper::setJavaVM(0xf533c000), pthread_self() = -563607248
,11-04 00:12:20.274  5679  5720 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-04 00:12:20.274  5679  5720 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-04 00:12:20.274  5679  5720 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-04 00:12:20.274  5679  5720 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-04 00:12:20.274  5679  5720 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-04 00:12:20.274  5679  5720 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c32f04 added. We now have 1 listener(s)
,11-04 00:12:20.277  5679  5720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-04 00:12:20.278  5679  5720 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 00:12:20.278  5679  5720 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 00:12:20.278  5679  5720 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-04 00:12:20.280  5679  5720 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97f55b3 added. We now have 1 listener(s)
11-04 00:12:20.280  5679  5720 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 00:12:20.285   930  3020 D WifiService: New client listening to asynchronous messages
,11-04 00:12:20.287  5679  5720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 00:12:20.287  5679  5720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-04 00:12:20.287  5679  5720 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-04 00:12:20.287  5679  5720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-04 00:12:20.287  5679  5720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-04 00:12:20.287  5679  5720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-04 00:12:20.287  5679  5720 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-04 00:12:20.288  5679  5720 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-04 00:12:20.385  5679  5679 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-04 00:12:20.874  5679  5727 W jxcore-log: Initializing JXcore engine
,11-04 00:12:20.874  5679  5727 W jxcore-log: JXcore engine is ready
,11-04 00:12:20.897  5727  5727 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12538 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-04 00:12:20.897  5727  5727 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16497]" dev="sockfs" ino=16497 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-04 00:12:20.897  5727  5727 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-04 00:12:20.897  5727  5727 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31639]" dev="sockfs" ino=31639 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-04 00:12:20.907  5679  5727 W jxcore-log: Starting JXcore engine
,11-04 00:12:20.957  5679  5727 W jxcore-log: Platform android
11-04 00:12:20.957  5679  5727 W jxcore-log: 
11-04 00:12:20.957  5679  5727 W jxcore-log: Process ARCH arm
11-04 00:12:20.957  5679  5727 W jxcore-log: 
,11-04 00:12:21.140  5679  5727 I jxcore-log: JXcore Cordova bridge is ready!
11-04 00:12:21.140  5679  5727 I jxcore-log: 
,11-04 00:12:21.140  5679  5727 W jxcore-log: JXcore engine is started
,11-04 00:12:21.150  5679  5720 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-04 00:12:21.157  5679  5679 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-04 00:12:23.070  3620  3620 I ConfigService: onDestroy
,11-04 00:12:24.559   930  3450 I ActivityManager: Killing 5025:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-04 00:12:29.947   930  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 00:12:30.748  5679  5727 I jxcore-log: 2016-11-03 23:12:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-04 00:12:30.748  5679  5727 I jxcore-log: 
,11-04 00:12:30.750  5679  5727 I jxcore-log: 2016-11-03 23:12:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-04 00:12:30.750  5679  5727 I jxcore-log: 
,11-04 00:12:30.757  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-04 00:12:30.757  5679  5727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 00:12:30.757  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:12:30.757  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:12:30.757  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 00:12:30.757  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 00:12:30.757  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 00:12:30.757  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 00:12:30.757  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 00:12:30.760  5679  5727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 00:12:30.762  5679  5727 I jxcore-log: 2016-11-03 23:12:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-04 00:12:30.762  5679  5727 I jxcore-log: 
11-04 00:12:30.764  5679  5727 I jxcore-log: 2016-11-03 23:12:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-04 00:12:30.764  5679  5727 I jxcore-log: 
,11-04 00:12:31.011  5679  5727 I jxcore-log: 2016-11-03 23:12:31 - DEBUG UnitTest_app: 'Running unit tests'
11-04 00:12:31.011  5679  5727 I jxcore-log: 
,11-04 00:12:31.012  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 00:12:31.012  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90c5a9e added. We now have 2 listener(s)
11-04 00:12:31.013  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 00:12:31.013  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 00:12:31.013  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 00:12:31.013  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:12:31.013  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212e97f added. We now have 2 listener(s)
11-04 00:12:31.013  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 00:12:31.014  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 00:12:31.015  5679  5727 D executeNativeTests: Running unit tests
,11-04 00:12:31.054  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 00:12:31.054  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c added. We now have 3 listener(s)
11-04 00:12:31.054  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 00:12:31.055  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 00:12:31.055  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 00:12:31.055  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 00:12:31.055  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 added. We now have 3 listener(s)
11-04 00:12:31.055  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 00:12:31.055  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 00:12:31.057  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 00:12:31.057  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 00:12:31.057  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 00:12:31.057  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-04 00:12:31.058  5679  5727 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-04 00:12:31.058  5679  5727 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 00:12:31.058  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 00:12:31.058  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-04 00:12:31.058  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 00:12:31.058  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 00:12:31.058  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:31.058  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:31.058  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:31.059  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:31.059  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:31.059  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 00:12:31.059  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c removed from the list
11-04 00:12:31.059  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:31.059  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 removed from the list
11-04 00:12:31.059  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:31.059  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.060  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.060  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.060  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.060  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 00:12:31.060  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:31.060  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:31.060  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
,11-04 00:12:31.061  5679  5727 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-04 00:12:31.061  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:31.061  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:31.061  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:31.061  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:31.061  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:31.061  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:31.061  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:31.061  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:31.061  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:31.061  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:31.062  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.062  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.062  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.062  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:31.062  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:31.062  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:31.062  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:31.064  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-04 00:12:31.064  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-04 00:12:31.064  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-04 00:12:31.065  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 00:12:31.065  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:31.065  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:31.065  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:31.065  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 00:12:31.066  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:31.066  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:31.066  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:31.066  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:31.066  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:31.066  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:31.066  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.066  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.066  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.066  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 00:12:31.066  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:31.066  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:31.066  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:31.067  5679  5727 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-04 00:12:31.068  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 00:12:31.068  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 00:12:31.082  5679  5727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 00:12:31.082  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:12:31.082  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:12:31.082  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 00:12:31.082  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 00:12:31.082  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 00:12:31.082  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 00:12:31.082  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 00:12:31.085  5679  5727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 00:12:31.085  5679  5727 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 00:12:31.086  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 00:12:31.086  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 00:12:31.086  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 00:12:31.086  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 00:12:31.086  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 00:12:31.089  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 00:12:31.091  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 00:12:31.092  5679  5727 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 00:12:31.092  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 00:12:31.093  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 00:12:31.096  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:31.096  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 00:12:31.097  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 00:12:31.097  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 00:12:31.097  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 00:12:31.099  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-04 00:12:31.100  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-04 00:12:31.100  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.100  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 00:12:31.100  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 00:12:31.100  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 00:12:31.100  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 00:12:31.100  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.101  5679  5727 D BluetoothAdapter: STATE_ON
,11-04 00:12:31.103  4645  4657 D BtGatt.GattService: registerClient() - UUID=084bc9df-257d-450a-91a9-a7cad307b373
,11-04 00:12:31.104  4645  4704 D BtGatt.GattService: onClientRegistered() - UUID=084bc9df-257d-450a-91a9-a7cad307b373, clientIf=5
,11-04 00:12:31.107  5679  5689 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 00:12:31.108  4645  4862 D BtGatt.GattService: start scan with filters
,11-04 00:12:31.116  4645  4709 D BtGatt.ScanManager: handling starting scan
11-04 00:12:31.117  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 00:12:31.117  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.117  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 00:12:31.117  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.117  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 00:12:31.117  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 00:12:31.117  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 00:12:31.117  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-04 00:12:31.117  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 00:12:31.118  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 00:12:31.118  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:12:31.118  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.118  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 00:12:31.118  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 00:12:31.118  4645  4709 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
,11-04 00:12:31.118  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.118  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.118  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:31.119  5679  5727 I io.jxcore.node.ConnectionHelper: start: OK
,11-04 00:12:31.120  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 00:12:31.125  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-04 00:12:31.125  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 00:12:31.125  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 00:12:31.125  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:12:31.125  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:12:31.126  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 00:12:31.126  4645  4704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 00:12:31.126  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 00:12:31.127  4645  4709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 00:12:31.134  4645  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 00:12:31.134  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 00:12:31.135  4645  4709 D BtGatt.ScanManager: Starting BLE batch scan
11-04 00:12:31.135  4645  4709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 00:12:31.147  4645  4704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 00:12:31.147  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 00:12:31.153  4645  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 00:12:31.153  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 00:12:31.627  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-04 00:12:31.628  5679  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 00:12:31.628  5679  5679 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 00:12:33.956   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:12:34.957   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:12:35.957   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:12:36.126  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:36.127  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:36.127  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 00:12:36.127  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 00:12:36.127  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 00:12:36.128  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:36.128  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 00:12:36.128  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 00:12:36.128  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 00:12:36.128  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 00:12:36.130  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.130  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:36.131  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.131  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 00:12:36.131  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:36.133  5679  5727 D BluetoothAdapter: STATE_ON
,11-04 00:12:36.134  4645  4861 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-04 00:12:36.134  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 00:12:36.136  4645  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 00:12:36.136  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:12:36.137  4645  4657 D BtGatt.GattService: stopScan() - queue size =1
,11-04 00:12:36.139  4645  4862 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 00:12:36.140  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 00:12:36.140  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.140  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 00:12:36.140  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.140  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.141  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.141  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.141  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 00:12:36.142  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.142  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.142  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.142  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 00:12:36.143  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 00:12:36.144  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 00:12:36.144  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.144  4645  4645 D BtGatt.ScanManager: awakened up at time 85063
11-04 00:12:36.146  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.146  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 00:12:36.146  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:36.146  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:36.146  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:36.147  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 00:12:36.147  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 00:12:36.147  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:36.147  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:36.147  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:12:36.147  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:36.147  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:36.146  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:12:36.147  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 00:12:36.148   930  3450 I ActivityManager: Killing 5433:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
11-04 00:12:36.147  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 00:12:36.148  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 00:12:36.149  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-04 00:12:36.149  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-04 00:12:36.149  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 00:12:36.149  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:12:36.149  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 00:12:36.149  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 00:12:36.150  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 00:12:36.152  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 00:12:36.152  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 00:12:36.152  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:12:36.153  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:12:36.153  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 00:12:36.207  4645  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-04 00:12:36.207  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 00:12:36.207  4645  4704 D BtGatt.GattService: current time is 85126274879
11-04 00:12:36.208  4645  4704 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -75, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -88, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-04 00:12:36.209  4645  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 00:12:36.210  4645  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-04 00:12:36.210  4645  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 00:12:36.210  4645  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-04 00:12:36.210  4645  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-04 00:12:36.215  4645  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 00:12:36.215  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:36.216  4645  4709 D BtGatt.ScanManager: stopping BLe Batch
11-04 00:12:36.220  4645  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 00:12:36.220  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:36.220  4645  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 00:12:36.225  4645  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 00:12:36.225  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:36.233  3978  5729 W CronetSyncConnectionRcs: Upload content type not set.
,11-04 00:12:36.296  4842  4885 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-04 00:12:36.297  4842  4842 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-04 00:12:36.655  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 00:12:36.958   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:12:37.959   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:12:38.960   602   602 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 00:12:41.179  5679  5727 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-04 00:12:41.186  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 00:12:41.187  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 00:12:41.200  5679  5727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 00:12:41.200  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:12:41.200  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:12:41.200  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 00:12:41.200  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 00:12:41.200  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 00:12:41.200  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 00:12:41.200  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 00:12:41.204  5679  5727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 00:12:41.205  5679  5727 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 00:12:41.205  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-04 00:12:41.205  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 00:12:41.205  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-04 00:12:41.205  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 00:12:41.206  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 00:12:41.209  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 00:12:41.212  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 00:12:41.212  5679  5727 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-04 00:12:41.212  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 00:12:41.219  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 00:12:41.219  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:41.219  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 00:12:41.221  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-04 00:12:41.221  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 00:12:41.221  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 00:12:41.226  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.226  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-04 00:12:41.226  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 00:12:41.226  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 00:12:41.226  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-04 00:12:41.226  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.227  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:12:41.229  4645  4841 D BtGatt.GattService: registerClient() - UUID=bb1c3c48-164f-4d94-ab88-0f82bbd6b564
,11-04 00:12:41.230  4645  4704 D BtGatt.GattService: onClientRegistered() - UUID=bb1c3c48-164f-4d94-ab88-0f82bbd6b564, clientIf=5
11-04 00:12:41.230  5679  5690 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 00:12:41.231  4645  4657 D BtGatt.GattService: start scan with filters
,11-04 00:12:41.235  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 00:12:41.235  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:41.235  4645  4709 D BtGatt.ScanManager: handling starting scan
11-04 00:12:41.235  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 00:12:41.235  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.235  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 00:12:41.235  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-04 00:12:41.235  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.235  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 00:12:41.236  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 00:12:41.236  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.236  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.236  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 00:12:41.237  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 00:12:41.237  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:41.242  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.242  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 00:12:41.242  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.242  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.243  5679  5727 I io.jxcore.node.ConnectionHelper: start: OK
11-04 00:12:41.243  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 00:12:41.245  4645  4704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-04 00:12:41.246  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:41.246  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:41.246  5679  5727 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 00:12:41.246  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:41.246  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 00:12:41.246  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 00:12:41.246  4645  4709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 00:12:41.246  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-04 00:12:41.246  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:41.246  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-04 00:12:41.251  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.251  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-04 00:12:41.251  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.252  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 00:12:41.252  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 00:12:41.252  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 00:12:41.254  4645  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-04 00:12:41.254  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 00:12:41.254  4645  4709 D BtGatt.ScanManager: Starting BLE batch scan
11-04 00:12:41.254  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.254  4645  4709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 00:12:41.254  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 00:12:41.255  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.255  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.255  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.255  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 00:12:41.255  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:41.256  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:12:41.256  4645  4862 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-04 00:12:41.256  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-04 00:12:41.257  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:12:41.258  4645  4657 D BtGatt.GattService: stopScan() - queue size =1
,11-04 00:12:41.262  4645  4841 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 00:12:41.262  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-04 00:12:41.262  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.262  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 00:12:41.262  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.262  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.263  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.263  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.263  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 00:12:41.263  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.263  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:41.263  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.263  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 00:12:41.263  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 00:12:41.263  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 00:12:41.264  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:41.266  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.266  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 00:12:41.266  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.266  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.266  4645  4704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 00:12:41.266  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:41.266  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:41.266  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 00:12:41.266  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 00:12:41.266  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 00:12:41.266  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:41.266  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:12:41.266  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:41.266  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:41.266  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 00:12:41.266  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:41.267  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:41.267  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 00:12:41.267  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.267  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 00:12:41.267  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 00:12:41.267  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.267  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-04 00:12:41.267  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 00:12:41.267  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.268  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.268  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.269  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.269  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.269  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 00:12:41.269  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:41.270  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:41.270  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.270  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.270  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:41.270  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:41.270  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:41.270  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:41.271  5679  5727 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-04 00:12:41.273  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 00:12:41.273  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 00:12:41.273  4645  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 00:12:41.273  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:41.275  4645  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 00:12:41.280  4645  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 00:12:41.280  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:41.280  4645  4704 E BtGatt.ContextMap: Context not found for ID 5
11-04 00:12:41.280  5679  5727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 00:12:41.280  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:12:41.280  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:12:41.280  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 00:12:41.280  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 00:12:41.280  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 00:12:41.280  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 00:12:41.280  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 00:12:41.283  5679  5727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 00:12:41.283  5679  5727 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 00:12:41.283  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 00:12:41.283  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 00:12:41.283  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-04 00:12:41.283  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 00:12:41.283  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 00:12:41.286  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 00:12:41.287  4645  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 00:12:41.287  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:41.288  4645  4709 D BtGatt.ScanManager: stopping BLe Batch
,11-04 00:12:41.289  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 00:12:41.289  5679  5727 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-04 00:12:41.289  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 00:12:41.289  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 00:12:41.292  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.292  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 00:12:41.293  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-04 00:12:41.293  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 00:12:41.293  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-04 00:12:41.294  4645  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 00:12:41.294  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:41.294  4645  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 00:12:41.299  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.299  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 00:12:41.299  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-04 00:12:41.299  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 00:12:41.299  4645  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 00:12:41.299  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 00:12:41.299  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:41.299  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.299  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:12:41.301  4645  4861 D BtGatt.GattService: registerClient() - UUID=f7adb635-78ca-4284-b285-4e1a30a45d8e
11-04 00:12:41.302  4645  4704 D BtGatt.GattService: onClientRegistered() - UUID=f7adb635-78ca-4284-b285-4e1a30a45d8e, clientIf=5
,11-04 00:12:41.302  5679  5689 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 00:12:41.303  4645  4841 D BtGatt.GattService: start scan with filters
,11-04 00:12:41.304  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 00:12:41.305  4645  4709 D BtGatt.ScanManager: handling starting scan
11-04 00:12:41.305  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.305  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 00:12:41.305  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.305  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 00:12:41.305  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-04 00:12:41.305  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.305  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 00:12:41.305  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 00:12:41.305  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.305  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.305  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-04 00:12:41.306  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 00:12:41.306  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:41.308  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.309  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 00:12:41.309  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.309  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:41.309  5679  5727 I io.jxcore.node.ConnectionHelper: start: OK
11-04 00:12:41.309  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 00:12:41.310  4645  4704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 00:12:41.310  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:41.311  4645  4709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 00:12:41.312  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.312  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.312  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.312  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:12:41.312  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 00:12:41.316  4645  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 00:12:41.316  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:41.316  4645  4709 D BtGatt.ScanManager: Starting BLE batch scan
11-04 00:12:41.316  4645  4709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 00:12:41.324  4645  4704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 00:12:41.324  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 00:12:41.329  4645  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 00:12:41.329  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 00:12:41.813  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-04 00:12:41.813  5679  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 00:12:41.813  5679  5679 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 00:12:46.309  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 00:12:46.310  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:46.310  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 00:12:46.310  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 00:12:46.310  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-04 00:12:46.310  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 00:12:46.310  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 00:12:46.311  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-04 00:12:46.311  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 00:12:46.311  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 00:12:46.311  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.312  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.312  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.312  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 00:12:46.312  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.314  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:12:46.315  4645  4841 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 00:12:46.316  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 00:12:46.317  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:12:46.317  4645  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 00:12:46.319  4645  4658 D BtGatt.GattService: stopScan() - queue size =1
,11-04 00:12:46.320  4645  4862 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 00:12:46.321  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 00:12:46.322  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.322  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-04 00:12:46.322  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.322  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.323  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.323  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:46.323  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 00:12:46.323  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.323  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.323  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.324  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 00:12:46.324  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 00:12:46.326  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 00:12:46.326  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:46.327  4645  4645 D BtGatt.ScanManager: awakened up at time 95246
11-04 00:12:46.329   930   940 I ActivityManager: Killing 5445:com.android.chrome/u0a39 (adj 15): empty #17
11-04 00:12:46.332  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.332  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 00:12:46.332  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.332  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:46.332  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:12:46.333  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:12:46.333  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 00:12:46.333  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 00:12:46.333  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-04 00:12:46.333  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 00:12:46.333  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:12:46.333  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 00:12:46.334  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 00:12:46.334  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 00:12:46.336  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 00:12:46.336  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 00:12:46.337  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:12:46.337  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:12:46.337  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 00:12:46.376  4645  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-04 00:12:46.376  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:46.376  4645  4704 D BtGatt.GattService: current time is 95295320217
11-04 00:12:46.377  4645  4704 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -75, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -85, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -91, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-04 00:12:46.377  4645  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-04 00:12:46.377  4645  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 00:12:46.378  4645  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-04 00:12:46.378  4645  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 00:12:46.378  4645  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-04 00:12:46.384  4645  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 00:12:46.385  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:46.385  4645  4709 D BtGatt.ScanManager: stopping BLe Batch
,11-04 00:12:46.391  4645  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 00:12:46.391  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:12:46.391  4645  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 00:12:46.396  4645  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 00:12:46.396  4645  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 00:12:46.838  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 00:12:46.839  5679  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 00:12:46.839  5679  5679 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 00:12:51.334  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 00:12:51.334  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 00:12:51.334  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 00:12:51.335  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 00:12:51.335  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 00:12:51.335  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 00:12:51.335  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:51.335  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:51.335  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.336  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
,11-04 00:12:51.336  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:51.336  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 00:12:51.339  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:51.344  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:51.345  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.345  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.346  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 00:12:51.346  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 00:12:51.346  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.346  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.348  5679  5727 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-04 00:12:51.349  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:51.350  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 00:12:51.350  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:51.350  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:51.350  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 00:12:51.350  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:51.351  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:12:51.351  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.351  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:51.351  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:51.354  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:51.354  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.354  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.354  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:51.354  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 00:12:51.354  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.354  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.356  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-04 00:12:51.356  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:51.357  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:51.357  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:51.357  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 00:12:51.357  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:51.357  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:51.357  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.357  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.357  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 00:12:51.358  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.360  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.360  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.360  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.360  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:51.360  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:51.360  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:12:51.360  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
,11-04 00:12:51.362  5679  5727 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-04 00:12:51.363  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 00:12:51.363  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:51.363  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:51.363  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:51.363  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:51.363  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:51.363  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.364  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
,11-04 00:12:51.364  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:51.364  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.366  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.366  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.366  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:51.366  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:51.366  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:51.366  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.366  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.367  5679  5727 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-04 00:12:51.368  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:51.368  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:51.368  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:51.368  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:51.368  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:51.368  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
,11-04 00:12:51.368  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.369  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.369  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:51.369  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.372  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.372  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.372  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.372  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:51.372  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:51.372  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.372  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
,11-04 00:12:51.373  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-04 00:12:51.374  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 00:12:51.374  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 00:12:51.374  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 00:12:51.374  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 00:12:51.374  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-04 00:12:51.374  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 00:12:51.374  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 00:12:51.374  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 00:12:51.375  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:51.375  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:51.375  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 00:12:51.375  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:51.375  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:51.375  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:51.375  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.375  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.375  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:51.376  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.377  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.377  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.377  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:51.377  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:51.377  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:51.377  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.378  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.379  5679  5727 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 00:12:51.379  5679  5727 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-04 00:12:51.379  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-04 00:12:51.383  5679  5727 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-04 00:12:51.383  5679  5727 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-04 00:12:51.383  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-04 00:12:51.384  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 00:12:51.384  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-04 00:12:51.384  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 00:12:51.384  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 00:12:51.384  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 00:12:51.384  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-04 00:12:51.384  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 00:12:51.384  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-04 00:12:51.384  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 00:12:51.384  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-04 00:12:51.384  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 00:12:51.385  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-04 00:12:51.385  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 00:12:51.385  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-04 00:12:51.385  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 00:12:51.385  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 00:12:51.385  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-04 00:12:51.385  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-04 00:12:51.385  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 00:12:51.385  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 00:12:51.385  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 00:12:51.386  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-04 00:12:51.386  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-04 00:12:51.386  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 00:12:51.387  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 00:12:51.387  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 00:12:51.387  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 00:12:51.387  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-04 00:12:51.387  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 00:12:51.387  5679  5727 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-04 00:12:51.387  5679  5727 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 00:12:51.388  5679  5727 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-04 00:12:51.388  5679  5727 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 00:12:51.388  5679  5727 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 00:12:51.388  5679  5727 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,11-04 00:12:51.388  5679  5727 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 00:12:51.388  5679  5727 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 00:12:51.388  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-04 00:12:51.393  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-04 00:12:51.394  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-04 00:12:51.394  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-04 00:12:51.395  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-04 00:12:51.395  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,11-04 00:12:51.395  5679  5727 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-04 00:12:51.395  5679  5727 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 00:12:51.395  5679  5727 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-04 00:12:51.395  5679  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-04 00:12:51.396  5679  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-04 00:12:51.396  5679  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-04 00:12:51.396  5679  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-04 00:12:51.396  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:51.396  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:51.397  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:51.397  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:51.397  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:51.397  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-04 00:12:51.406  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:51.406  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.406  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.406  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:51.406  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.407  5679  5733 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-04 00:12:51.407  5679  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 00:12:51.407  5679  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
,11-04 00:12:51.407  5679  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-04 00:12:51.407  5679  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
11-04 00:12:51.407  5679  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
11-04 00:12:51.408  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.409  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.409  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.409  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:51.409  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 00:12:51.409  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.409  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.410  5679  5733 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-04 00:12:51.410  5679  5727 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-04 00:12:51.410  5679  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-04 00:12:51.410  5679  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
11-04 00:12:51.411  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:51.411  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:51.411  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:51.411  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:51.411  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 00:12:51.411  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:51.411  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.412  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.412  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:51.412  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.407  4658  4658 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32421]" dev="sockfs" ino=32421 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 00:12:51.407  4658  4658 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32421]" dev="sockfs" ino=32421 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 00:12:51.414  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:51.414  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.414  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.414  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:51.414  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:51.414  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.414  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.415  5679  5727 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-04 00:12:51.416  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 00:12:51.416  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:51.416  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:51.416  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:51.416  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:51.416  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:51.416  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.416  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.416  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:51.416  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.417  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.417  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.417  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.417  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:51.418  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 00:12:51.418  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.418  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.418  5679  5727 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-04 00:12:51.419  5679  5727 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,11-04 00:12:51.419  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 00:12:51.419  5679  5727 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-04 00:12:51.419  5679  5727 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 00:12:51.420  5679  5727 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-04 00:12:51.420  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 00:12:51.420  5679  5727 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-04 00:12:51.420  5679  5727 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 00:12:51.420  5679  5727 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,11-04 00:12:51.420  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 00:12:51.420  5679  5727 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-04 00:12:51.420  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:51.420  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:51.420  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:51.420  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:51.420  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 00:12:51.420  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:51.420  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.420  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.420  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:51.421  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.422  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:51.422  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.422  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:51.422  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:51.422  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:51.422  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.422  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.423  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 00:12:51.423  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:51.423  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:51.423  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:51.423  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:51.423  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 00:12:56.424  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:12:56.424  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:56.424  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:56.425  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:56.425  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
,11-04 00:12:56.425  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:56.425  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 00:12:56.426  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:56.426  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:56.426  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:56.426  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:56.426  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:56.427  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
,11-04 00:12:56.427  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:56.427  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:56.430  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.431  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:56.431  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.431  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 00:12:56.432  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:56.432  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:12:56.432  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
,11-04 00:12:56.437  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-04 00:12:56.438  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 00:12:56.438  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 00:12:56.444  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 00:12:56.446  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 00:12:56.446  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-04 00:12:56.447  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 00:12:56.447  5679  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-04 00:12:56.448  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 00:12:56.448  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 00:12:56.448  5679  5679 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-04 00:12:56.449  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:56.449  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 00:12:56.449  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-04 00:12:56.450  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 00:12:56.450  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 00:12:56.451  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 00:12:56.451  5679  5735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 00:12:56.451  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 00:12:56.452  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
,11-04 00:12:56.452  5679  5679 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 00:12:56.452  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:56.452  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-04 00:12:56.452  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 00:12:56.452  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 00:12:56.452  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.454  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.451  4841  4841 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32424]" dev="sockfs" ino=32424 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 00:12:56.454  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 00:12:56.454  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:56.454  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.455  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
,11-04 00:12:56.455  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:12:56.455  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:56.455  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 00:12:56.455  5679  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 00:12:56.455  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:12:56.455  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 00:12:56.455  5679  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 00:12:56.455  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:56.455  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 00:12:56.455  5679  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 00:12:56.455  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 00:12:56.456  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:56.456  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:56.456  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
,11-04 00:12:56.456  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:56.456  5679  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 00:12:56.456  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.456  5679  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:56.458  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.458  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.458  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.451  4841  4841 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32424]" dev="sockfs" ino=32424 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 00:12:56.459  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:56.459  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:56.459  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:56.459  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:56.461  5679  5727 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-04 00:12:56.461  5679  5727 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 00:12:56.461  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 00:12:56.461  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 00:12:56.461  5679  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-04 00:12:56.462  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:56.462  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:56.462  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:56.462  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:56.462  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:56.462  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
,11-04 00:12:56.462  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:56.462  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:56.462  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:12:56.463  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.464  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.465  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:56.465  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.465  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:56.465  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:56.465  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:56.465  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
,11-04 00:12:56.471  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 00:12:56.471  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:56.471  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:56.471  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:12:56.471  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:56.471  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:56.471  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:12:56.471  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:56.472  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 00:12:56.472  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:56.473  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:56.473  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.473  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.474  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:12:56.474  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:56.474  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:12:56.474  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:56.476  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:12:56.476  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:12:56.476  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:12:56.477  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 00:12:56.477  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:12:56.477  5679  5727 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643a17c not in the list
11-04 00:12:56.477  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:56.477  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
11-04 00:12:56.477  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 00:12:56.477  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:12:56.479  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.479  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.479  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:12:56.479  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 00:12:56.479  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:12:56.479  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:12:56.479  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7ba05 not in the list
,11-04 00:12:56.481  5679  5727 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-04 00:12:56.482  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 00:12:56.482  5679  5727 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-04 00:12:56.482  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 00:12:56.483  5679  5727 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-04 00:12:56.483  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-04 00:12:56.486  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-04 00:12:56.487  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-04 00:12:56.487  5679  5727 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-04 00:12:56.487  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 00:12:56.487  5679  5727 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-04 00:12:56.487  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 00:12:56.487  5679  5727 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-04 00:12:56.488  5679  5727 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-04 00:12:56.488  5679  5727 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-04 00:12:56.488  5679  5727 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-04 00:12:56.489  5679  5727 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-04 00:12:56.489  5679  5727 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-04 00:12:56.489  5679  5727 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-04 00:12:56.489  5679  5727 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-04 00:12:56.490  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:12:56.490  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@78d9e0a added. We now have 3 listener(s)
11-04 00:12:56.490  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 00:12:56.492  5679  5727 D BluetoothAdapter: enable(): BT is already enabled..!
,11-04 00:12:56.493   930  3827 D WifiService: setWifiEnabled: true pid=5679, uid=10077
11-04 00:12:56.493   930  3827 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 00:12:56.539  4645  4836 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-04 00:12:56.539  4645  4839 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-04 00:12:56.956  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 00:13:00.466   930  5407 D NetlinkSocketObserver: NeighborEvent{elapsedMs=109383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-04 00:13:01.500  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 00:13:01.500  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32f867b added. We now have 4 listener(s)
11-04 00:13:01.500  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 00:13:01.508  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:13:01.508  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32f867b removed from the list
11-04 00:13:01.508  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:13:01.510  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 00:13:01.510  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@457ec98 added. We now have 4 listener(s)
11-04 00:13:01.510  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 00:13:01.512  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:13:01.512  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@457ec98 removed from the list
,11-04 00:13:01.512  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 00:13:01.514  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 00:13:01.514  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9163cf1 added. We now have 4 listener(s)
11-04 00:13:01.514  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 00:13:01.518   930  3844 D WifiService: setWifiEnabled: false pid=5679, uid=10077
11-04 00:13:01.518   930  3844 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-04 00:13:01.521   930  3019 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-04 00:13:01.521   930  3019 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 00:13:01.521   930  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 00:13:01.521   930  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 00:13:01.526  4645  4700 D BluetoothAdapterState: Current state: ON, message: 23
,11-04 00:13:01.526  4645  4700 D BluetoothAdapterProperties: Setting state to 13
11-04 00:13:01.526  4645  4700 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 00:13:01.526  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 00:13:01.526  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 00:13:01.527  4645  4700 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 00:13:01.527  4645  4700 I BluetoothAdapterState: Entering PendingCommandState
,11-04 00:13:01.529  4645  4645 D BluetoothMapService: onReceive
11-04 00:13:01.529  4645  4645 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 00:13:01.529  4645  4645 D BluetoothMapService: STATE_TURNING_OFF
11-04 00:13:01.530  4645  4645 D BluetoothMapService: MAP Service closeService in
11-04 00:13:01.530  4645  4645 D BluetoothMapMasInstance0: MAP Service shutdown
11-04 00:13:01.530  4645  4645 D ObexServerSockets0: shutdown(block = true)
11-04 00:13:01.530  4645  4645 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 00:13:01.531  4645  4645 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 00:13:01.531  4645  4864 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-04 00:13:01.531  4645  4865 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 00:13:01.531  4645  4839 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-04 00:13:01.535  4645  4645 I BtOppRfcommListener: stopping Accept Thread
11-04 00:13:01.535  4645  5360 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-04 00:13:01.536  4645  5360 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-04 00:13:01.537   930  5408 D DhcpClient: Clearing IP address
11-04 00:13:01.537   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-04 00:13:01.544   509   923 D CommandListener: Setting iface cfg
,11-04 00:13:01.546  3620  5458 V NativeCrypto: Read error: ssl=0x7f76167000: I/O error during system call, Connection timed out
,11-04 00:13:01.549  3620  5458 V NativeCrypto: SSL shutdown failed: ssl=0x7f76167000: I/O error during system call, Broken pipe
11-04 00:13:01.550   930   943 I ActivityManager: Start proc 5739:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-04 00:13:01.550  4645  4704 D BluetoothAdapterProperties: Scan Mode:20
,11-04 00:13:01.551  4645  4700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-04 00:13:01.552   930  3450 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-04 00:13:01.552   930  5406 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-04 00:13:01.555  4645  4645 D HeadsetService: Received stop request...Stopping profile...
,11-04 00:13:01.556   930  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-04 00:13:01.556   930  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-04 00:13:01.557   930  5406 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-04 00:13:01.557  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:01.558  5679  5727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 00:13:01.558  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:01.558  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:01.558  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 00:13:01.558  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 00:13:01.558  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 00:13:01.558  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 00:13:01.558  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 00:13:01.559  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:01.559  5679  5727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 00:13:01.559  5679  5727 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 00:13:01.563   599   599 E Parcel  : Reading a NULL string not supported here.
,11-04 00:13:01.563  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 00:13:01.564  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 00:13:01.564  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:01.564  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:01.564  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 00:13:01.564  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 00:13:01.564  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 00:13:01.564  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 00:13:01.564  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 00:13:01.564  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:01.565  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 00:13:01.566  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 00:13:01.567   930   930 D RttService: SCAN_AVAILABLE : 1
11-04 00:13:01.567   930  3072 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 00:13:01.569   930  5409 D DhcpClient: Receive thread stopped
,11-04 00:13:01.569  3796  4049 D BluetoothHeadset: Proxy object disconnected
11-04 00:13:01.570   930   930 D BluetoothHeadset: Proxy object disconnected
11-04 00:13:01.570   930   930 D BluetoothHeadset: Proxy object disconnected
11-04 00:13:01.570   930   930 D BluetoothHeadset: Proxy object disconnected
11-04 00:13:01.570  4645  4645 D A2dpService: Received stop request...Stopping profile...
11-04 00:13:01.570  4645  4856 D A2dpStateMachine: Exit Disconnected: -1
11-04 00:13:01.571   930  3021 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-04 00:13:01.572  3123  3139 D BluetoothHeadset: Proxy object disconnected
11-04 00:13:01.572  3758  3888 W QCNEJ   : |CORE| network lost: 100
11-04 00:13:01.572  3758  3888 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-04 00:13:01.573  3123  3123 D HeadsetProfile: Bluetooth service disconnected
11-04 00:13:01.573  4645  4645 D HidService: Received stop request...Stopping profile...
11-04 00:13:01.574  4645  4645 D HidService: Stopping Bluetooth HidService
11-04 00:13:01.575  3123  3123 D BluetoothA2dp: Proxy object disconnected
11-04 00:13:01.575  4645  4645 D HealthService: Received stop request...Stopping profile...
11-04 00:13:01.575  3123  3123 D BluetoothInputDevice: Proxy object disconnected
11-04 00:13:01.575  3123  3123 D HidProfile: Bluetooth service disconnected
,11-04 00:13:01.575   930   930 D BluetoothA2dp: Proxy object disconnected
,11-04 00:13:01.576  4645  4645 V BluetoothAdapterState: isTurningOff()=true
,11-04 00:13:01.576  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:01.576  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:01.576  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:01.577  4645  4645 D PanService: Received stop request...Stopping profile...
11-04 00:13:01.577  3123  3123 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 00:13:01.578  3123  3123 D PanProfile: Bluetooth service disconnected
11-04 00:13:01.578  4645  4645 D BluetoothMapService: Received stop request...Stopping profile...
11-04 00:13:01.578  4645  4645 D BluetoothMapService: stop()
,11-04 00:13:01.578  4645  4645 D BluetoothMapAppObserver: deinitObservers()
11-04 00:13:01.579  4645  4645 D BluetoothMapAppObserver: removeReceiver()
,11-04 00:13:01.579   930  3019 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-04 00:13:01.580  3123  3123 D BluetoothMap: Proxy object disconnected
11-04 00:13:01.581  3123  3123 D MapProfile: Bluetooth service disconnected
11-04 00:13:01.581  4645  4645 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 00:13:01.581  4645  4645 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 00:13:01.581  4645  4836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 00:13:01.581  4645  4836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 00:13:01.582  4645  4836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 00:13:01.582  4645  4704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 00:13:01.582  4645  4645 D SapService: Received stop request...Stopping profile...
,11-04 00:13:01.582  4645  4704 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-04 00:13:01.582  4645  4645 V SapService: stop()
11-04 00:13:01.584  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:01.584  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:01.584  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:01.584  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 00:13:01.585  4645  4836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 00:13:01.585  4645  4645 V BluetoothAdapterState: isTurningOff()=true
,11-04 00:13:01.585  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:01.585  4645  4836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 00:13:01.585  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 00:13:01.585  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:01.585  4645  4836 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 00:13:01.585  4645  4836 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 00:13:01.585  4645  4836 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 00:13:01.585  4645  4645 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 00:13:01.585  4645  4836 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 00:13:01.586  4645  4645 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 00:13:01.586  4645  4704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 00:13:01.586  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:01.586  4645  4645 V BluetoothAdapterState: isTurningOn()=false
,11-04 00:13:01.586  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:01.586  4645  4704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 00:13:01.586  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:01.586  4645  4645 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 00:13:01.586  4645  4704 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 00:13:01.586  4645  4645 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 00:13:01.587  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:01.587  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:01.587  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:01.587  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:01.587  4645  4645 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 00:13:01.587  4645  4645 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 00:13:01.588  4645  4645 D BluetoothMapService: MAP Service closeService in
11-04 00:13:01.588  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:01.588  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:01.588  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:01.588  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 00:13:01.588  4645  4645 D BluetoothMapService: cleanup()
11-04 00:13:01.588  4645  4645 D BluetoothMapService: MAP Service closeService in
11-04 00:13:01.588  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:01.588  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:01.588  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:01.588  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:01.589  4645  4700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 00:13:01.589  4645  4700 D BluetoothAdapterProperties: Setting state to 15
11-04 00:13:01.589  4645  4700 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 00:13:01.590  3123  3139 D BluetoothMap: onBluetoothStateChange: up=false
11-04 00:13:01.590  4645  4700 I BluetoothAdapterState: Entering BleOnState
11-04 00:13:01.591   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 00:13:01.591  3123  3140 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 00:13:01.593  3123  3878 D BluetoothPan: onBluetoothStateChange on: false
11-04 00:13:01.593  3123  3139 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 00:13:01.594  3796  3826 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 00:13:01.594   930  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 00:13:01.594  3123  3140 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 00:13:01.594   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 00:13:01.594   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 00:13:01.594   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 00:13:01.595  3123  3878 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 00:13:01.596  4645  4700 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-04 00:13:01.596  4645  4700 D BluetoothAdapterProperties: Setting state to 16
11-04 00:13:01.596  4645  4700 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-04 00:13:01.596  4645  4700 D BluetoothAdapterProperties: onBleDisable
11-04 00:13:01.596  4645  4700 I BluetoothAdapterState: Entering PendingCommandState
11-04 00:13:01.597  4645  4701 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 00:13:01.597  4645  4704 D BluetoothAdapterProperties: Scan Mode:20
11-04 00:13:01.598  4645  4836 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 00:13:01.598  4645  4836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 00:13:01.600  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:01.600  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 00:13:01.600  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:01.600  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:01.600  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 00:13:01.600  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 00:13:01.600  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 00:13:01.600  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 00:13:01.600  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 00:13:01.601  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 00:13:01.619   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-04 00:13:01.621  5739  5739 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-04 00:13:01.634  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 00:13:01.639   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c424749:true
11-04 00:13:01.640   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-04 00:13:01.640   509   923 D CommandListener: Clearing all IP addresses on wlan0
11-04 00:13:01.640  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 00:13:01.641   930  3021 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-04 00:13:01.641   930  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 00:13:01.642   930  3019 D DhcpClient: doQuit
11-04 00:13:01.642   930  3019 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 00:13:01.643   930  5408 D DhcpClient: onQuitting
11-04 00:13:01.643  3475  3475 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-04 00:13:01.646   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-04 00:13:01.649  5332  5332 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@be7ec35 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-04 00:13:01.650  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:01.650  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 00:13:01.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:01.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:01.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 00:13:01.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 00:13:01.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 00:13:01.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 00:13:01.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 00:13:01.651  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:01.651  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 00:13:01.652  3978  3978 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-04 00:13:01.659   930  3173 I ActivityManager: Start proc 5757:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-04 00:13:01.663  3475  3475 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 00:13:01.664  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 00:13:01.667  3475  3475 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-04 00:13:01.675  5739  5739 D LocalBluetoothProfileManager: Adding local MAP profile
,11-04 00:13:01.678  5739  5739 D BluetoothMap: Create BluetoothMap proxy object
,11-04 00:13:01.694  3475  3475 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 00:13:01.699  5757  5757 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-04 00:13:01.700  5739  5739 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
11-04 00:13:01.702   509   923 E Netd    : netlink response contains error (No such file or directory)
11-04 00:13:01.703   930  3021 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-04 00:13:01.704   930  3021 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-04 00:13:01.705  3475  3475 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 00:13:01.714  5739  5739 D DockEventReceiver: finishStartingService: stopping service
,11-04 00:13:01.716   930  3451 I ActivityManager: Killing 4465:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-04 00:13:01.805  4645  4704 I bt_hci  : shut_down
,11-04 00:13:01.810  4645  4710 D bt_hwcfg: hw_epilog_process
11-04 00:13:01.810  4645  4710 I bt_vendor: low_power_mode_cb
11-04 00:13:01.810   930  3019 D wifi    : In wifi stop Hal
11-04 00:13:01.810   930  3019 D wifi    : halHandle = 0x7f74fd1b80, mVM = 0x7f9160d140, mCls = 0x1009fa
11-04 00:13:01.810   930  3474 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 00:13:01.811   930  3474 D WifiHAL : Got a signal to exit!!!
11-04 00:13:01.811   930  3474 I WifiHAL : Exit wifi_event_loop
11-04 00:13:01.811   930  3019 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-04 00:13:01.811   930  3019 E WifiHAL : Event processing terminated
11-04 00:13:01.811   930  3019 D wifi    : In wifi cleaned up handler
11-04 00:13:01.811   930  3019 I WifiHAL : Internal cleanup completed
11-04 00:13:01.812  4546  4546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 00:13:01.812  3724  4218 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 00:13:01.813  4645  4710 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-04 00:13:01.813  4645  4710 I bt_vendor: epilog_cb
11-04 00:13:01.813  4645  4710 I bt_hci  : epilog_finished_callback
11-04 00:13:01.814  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 00:13:01.815  4645  4704 I bt_hci_h4: hal_close
11-04 00:13:01.815  4645  4704 I bt_userial_vendor: device fd = 54 close
11-04 00:13:01.835   930  3474 D wifi    : set interface wlan0 flags (DOWN)
11-04 00:13:01.835   930  3019 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 00:13:01.897   509   923 E Netd    : netlink response contains error (No such file or directory)
,11-04 00:13:01.909  5757  5757 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-04 00:13:01.909  5757  5757 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 00:13:01.909  5757  5757 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 00:13:01.909  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 00:13:01.910  5757  5757 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 00:13:01.910  5757  5757 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.k.d(PG:583)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 00:13:01.910  5757  5757 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 00:13:01.910  5757  5757 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 00:13:01.910  5757  5757 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 00:13:01.910  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 00:13:01.914  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 00:13:01.919  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 00:13:01.926  4645  4701 D bt_stack_manager: event_shut_down_stack finished.
11-04 00:13:01.926  4645  4700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-04 00:13:01.927  4645  4700 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-04 00:13:01.928  4645  4645 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 00:13:01.928  4645  4645 D BtGatt.GattService: Received stop request...Stopping profile...
11-04 00:13:01.928  4645  4645 D BtGatt.GattService: stop()
11-04 00:13:01.928  4645  4645 D BtGatt.AdvertiseManager: advertise clients cleared
11-04 00:13:01.932  4645  4645 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:01.932  5739  5739 D DockEventReceiver: finishStartingService: stopping service
11-04 00:13:01.932  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:01.932  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:01.932  4645  4645 V BluetoothAdapterState: isBleTurningOff()=true
11-04 00:13:01.932  4645  4700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-04 00:13:01.932  4645  4700 D BluetoothAdapterProperties: Setting state to 10
11-04 00:13:01.932  4645  4700 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 00:13:01.932  4645  4700 I BluetoothAdapterState: Entering OffState
11-04 00:13:01.933   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-04 00:13:01.933  4015  4015 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-04 00:13:01.939  4645  4645 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-04 00:13:01.939  4645  4645 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 00:13:01.939  4645  4645 I BluetoothServiceJni: cleanupNative: return from cleanup
11-04 00:13:01.941  4645  4701 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-04 00:13:01.947  4015  4015 D SystemUpdateService: onCreate
,11-04 00:13:01.951  4645  4701 D bt_stack_manager: event_clean_up_stack finished.
11-04 00:13:01.951  4015  4015 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-04 00:13:01.964  4015  4015 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-04 00:13:01.968  4645  4645 I art     : System.exit called, status: 0
11-04 00:13:01.968  4645  4645 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-04 00:13:01.970  4015  4241 I iu.UploadsManager: num queued entries: 0
11-04 00:13:01.971  4015  4241 I iu.UploadsManager: num updated entries: 0
11-04 00:13:01.989  4015  4015 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 00:13:01.990  4015  4015 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-04 00:13:01.991  4015  5797 I SystemUpdateService: active receiver: enabled
,11-04 00:13:02.002   930  3844 I ActivityManager: Start proc 5799:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-04 00:13:02.009  4015  4241 I iu.SyncManager: NEXT; no task
,11-04 00:13:02.012  4015  5797 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 00:13:02.025   930  3449 I ActivityManager: Process com.android.bluetooth (pid 4645) has died
,11-04 00:13:02.037   930   947 D Tethering: InitialState.processMessage what=4
,11-04 00:13:02.040   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 00:13:02.045  5799  5799 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
11-04 00:13:02.046  4015  5797 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-04 00:13:02.046  4015  5797 I SystemUpdateService: now status is 0 (complete)
11-04 00:13:02.047  4015  5797 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 00:13:02.047  4015  5797 I SystemUpdateService: file has been verified
11-04 00:13:02.047  4015  5797 I SystemUpdateService: OTA package size = 21989297
,11-04 00:13:02.053  5799  5799 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 00:13:02.061  5799  5799 D SprintDMHelper: simOperator: 
,11-04 00:13:02.061  5799  5799 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 00:13:02.070  4015  5797 I SystemUpdateService: showing system update notification
,11-04 00:13:02.073   930  3449 I ActivityManager: Start proc 5811:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-04 00:13:02.073   930  3449 I ActivityManager: Killing 5115:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-04 00:13:02.148   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 00:13:02.180  4015  4015 D SystemUpdateService: onDestroy
,11-04 00:13:02.181   930  3819 I ActivityManager: Killing 5475:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-04 00:13:02.241   930  3844 I ActivityManager: Start proc 5827:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-04 00:13:02.242   930  3844 I ActivityManager: Killing 5332:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-04 00:13:02.299  5827  5827 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-04 00:13:02.307   930  3172 I ActivityManager: Killing 5519:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-04 00:13:02.372  5757  5786 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-04 00:13:02.383   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cec7562:true
,11-04 00:13:03.961   602   602 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-04 00:13:03.961   602   602 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-04 00:13:06.561   930  3827 D WifiService: setWifiEnabled: true pid=5679, uid=10077
,11-04 00:13:06.562   930  3827 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 00:13:06.569   509   923 D SoftapController: Softap fwReload - Ok
,11-04 00:13:06.575   509   923 D CommandListener: Setting iface cfg
,11-04 00:13:06.575   509   923 D CommandListener: Trying to bring down wlan0
,11-04 00:13:06.577   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-04 00:13:06.582   930  3019 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 00:13:07.152   930  3019 D wifi    : set interface wlan0 flags (UP)
11-04 00:13:07.152   930  3019 I WifiHAL : Initializing wifi
11-04 00:13:07.152   930  3019 I WifiHAL : Creating socket
11-04 00:13:07.154   930  3019 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-04 00:13:07.155   930  3019 D wifi    : Did set static halHandle = 0x7f74fd1b80
11-04 00:13:07.155   930  3019 D wifi    : halHandle = 0x7f74fd1b80, mVM = 0x7f9160d140, mCls = 0x193e
11-04 00:13:07.155   930  3019 D wifi    : array field set
11-04 00:13:07.155   930  3019 I WifiNative-HAL: interface[0] = wlan0
11-04 00:13:07.156   930  5844 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547423591296
11-04 00:13:07.157   930  5844 D wifi    : waitForHalEvents called, vm = 0x7f9160d140, obj = 0x193e, env = 0x7f74ffd580
,11-04 00:13:07.160   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 00:13:07.223  5846  5846 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 00:13:07.258   930  3019 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 00:13:07.260  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 00:13:07.269  5846  5846 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 00:13:07.330  5846  5846 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 00:13:07.330  5846  5846 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 00:13:07.351   930  3019 D WifiConfigStore: Loading config and enabling all networks 
,11-04 00:13:07.352  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:07.352  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 00:13:07.352  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:07.352  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:07.352  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 00:13:07.352  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 00:13:07.352  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 00:13:07.352  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 00:13:07.352  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 00:13:07.352  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:07.352  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 00:13:07.379   930  3019 D WifiConfigStore: loaded 0 passpoint configs
,11-04 00:13:07.380   930  3019 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-04 00:13:07.381   930  3019 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-04 00:13:07.381   930  3019 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-04 00:13:07.382   930  3019 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-04 00:13:07.382   930  3019 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-04 00:13:07.383   930  3019 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-04 00:13:07.383   930  3019 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 00:13:07.383   930  3019 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 00:13:07.383   930  3019 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-04 00:13:07.384   930  3019 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-04 00:13:07.384   930  3019 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 00:13:07.384   930  3019 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 00:13:07.386   930  3019 D WifiNative-HAL: Setting external_sim to 1
,11-04 00:13:07.386   930  3019 D wifi    : setting dfs flag to true, 0x7f78b3dc20
11-04 00:13:07.386   930  3019 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 00:13:07.386   930  3019 D wifi    : setting scan oui 0x7f78b3dc20
11-04 00:13:07.386  4546  4546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 00:13:07.387   930  3019 D WifiHAL : Sending mac address OUI
,11-04 00:13:07.390   930  3019 E native  : do suspend false
,11-04 00:13:07.397   930  3019 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-04 00:13:07.397   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-04 00:13:07.398   930   930 D RttService: SCAN_AVAILABLE : 3
11-04 00:13:07.398   930  3072 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 00:13:07.399   509   923 D CommandListener: Setting iface cfg
,11-04 00:13:07.402   930  3007 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
,11-04 00:13:07.402   930  3007 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 00:13:07.410   930  3007 D WifiNative-HAL: p2pGetDeviceAddress
11-04 00:13:07.410   930  3007 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 00:13:07.431   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=116350 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=30 mControllerEnergyUsed=114 }
,11-04 00:13:08.962   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:09.953   930  3019 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 7, 8 -> obsolete
,11-04 00:13:09.963   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:10.477  5846  5846 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 00:13:10.480  5846  5846 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 00:13:10.487  5846  5846 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 00:13:10.492  5846  5846 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 00:13:10.540   930  3019 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-04 00:13:10.541   930  3019 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-04 00:13:10.541   930  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 00:13:10.553   930  3019 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 00:13:10.583   930  3019 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 00:13:10.590  5846  5846 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 00:13:10.964   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:11.016  5846  5846 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 00:13:11.047  5846  5846 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 00:13:11.047  5846  5846 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 00:13:11.057   930  3019 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 00:13:11.058   930  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 00:13:11.058   930  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 00:13:11.076   930  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 00:13:11.092   509   923 D CommandListener: Setting iface cfg
,11-04 00:13:11.099   930  3019 D WifiStateMachine: Start Dhcp Watchdog 2
,11-04 00:13:11.106   930  5861 D DhcpClient: Receive thread started
,11-04 00:13:11.109   930  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 00:13:11.109   930  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-04 00:13:11.110   930  3021 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-04 00:13:11.190   930  3019 E native  : do suspend false
,11-04 00:13:11.201   930  5860 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 00:13:11.226   930  5861 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172719, domain null
,11-04 00:13:11.226   930  5860 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172719 seconds
,11-04 00:13:11.228   930  5860 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 00:13:11.240   930  5861 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-04 00:13:11.241   930  5860 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 00:13:11.244   509   923 D CommandListener: Setting iface cfg
,11-04 00:13:11.249   930  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 00:13:11.254   930  5860 D DhcpClient: Scheduling renewal in 86399s
,11-04 00:13:11.266   930  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-04 00:13:11.267   930  3019 D WifiConfigStore: No blacklist allowed without epno enabled
,11-04 00:13:11.268   930  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-04 00:13:11.270   930  3021 D ConnectivityService: Adding iface wlan0 to network 101
,11-04 00:13:11.282   930  3019 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 00:13:11.325   930  3021 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-04 00:13:11.325   930  3021 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-04 00:13:11.330   930  3021 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-04 00:13:11.334   930  3021 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-04 00:13:11.336   930  3021 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-04 00:13:11.344   930  3021 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 00:13:11.349   930  3021 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-04 00:13:11.350   930  3021 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-04 00:13:11.350   930  3021 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-04 00:13:11.350   930  3021 D ConnectivityService:    accepting network in place of null
11-04 00:13:11.350   930  3019 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-04 00:13:11.350   930  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 00:13:11.351   930  3021 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 00:13:11.364   930  5859 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120282, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 00:13:11.374   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 00:13:11.401   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 00:13:11.407   930  3021 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-04 00:13:11.407   930  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 00:13:11.407  3758  3888 W QCNEJ   : |CORE| network available: 101
11-04 00:13:11.408   930  3021 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-04 00:13:11.409   930   947 D Tethering: MasterInitialState.processMessage what=3
11-04 00:13:11.411  3758  3888 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-04 00:13:11.412  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:11.412  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 00:13:11.412  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:11.412  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:11.412  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 00:13:11.412  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 00:13:11.412  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 00:13:11.412  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 00:13:11.412  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 00:13:11.412  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:11.413  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 00:13:11.413  3758  3888 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-04 00:13:11.413  3758  3888 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-04 00:13:11.420  3978  3978 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-04 00:13:11.423  4015  4015 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 00:13:11.426  4015  4015 D SystemUpdateService: onCreate
,11-04 00:13:11.430  4015  4015 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 00:13:11.440  4015  4015 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 00:13:11.445  4015  4241 I iu.UploadsManager: num queued entries: 0
,11-04 00:13:11.445  4015  4241 I iu.UploadsManager: num updated entries: 0
,11-04 00:13:11.446  4015  4241 I iu.SyncManager: NEXT; no task
,11-04 00:13:11.448  4015  5870 I SystemUpdateService: active receiver: enabled
,11-04 00:13:11.451   930  5858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 00:13:11.451  4015  4015 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 00:13:11.453  4015  4015 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 00:13:11.455  5799  5799 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 00:13:11.458  5799  5799 D SprintDMHelper: simOperator: 
11-04 00:13:11.458  5799  5799 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 00:13:11.481  4015  5870 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 00:13:11.487  4015  5870 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 00:13:11.487  4015  5870 I SystemUpdateService: now status is 0 (complete)
11-04 00:13:11.487  4015  5870 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 00:13:11.487  4015  5870 I SystemUpdateService: file has been verified
11-04 00:13:11.487  4015  5870 I SystemUpdateService: OTA package size = 21989297
,11-04 00:13:11.493  4015  5870 I SystemUpdateService: showing system update notification
,11-04 00:13:11.501   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 00:13:11.502  4015  4015 D SystemUpdateService: onDestroy
,11-04 00:13:11.506   930  5858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 23:13:11 GMT], X-Android-Received-Millis=[1478214791505], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478214791477]}
,11-04 00:13:11.507   930  3021 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 00:13:11.507   930  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-04 00:13:11.507   930  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-04 00:13:11.508   930  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 00:13:11.566   930  3450 D WifiService: setWifiEnabled: false pid=5679, uid=10077
11-04 00:13:11.566   930  3450 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 00:13:11.567   930  3019 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-04 00:13:11.567   930  3019 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 00:13:11.568   930  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 00:13:11.568   930  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 00:13:11.577   930  5860 D DhcpClient: Clearing IP address
11-04 00:13:11.577   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-04 00:13:11.579   509   923 D CommandListener: Setting iface cfg
,11-04 00:13:11.584  3620  5877 V NativeCrypto: Read error: ssl=0x7f76167000: I/O error during system call, Connection timed out
,11-04 00:13:11.585  3620  5877 V NativeCrypto: SSL shutdown failed: ssl=0x7f76167000: I/O error during system call, Broken pipe
,11-04 00:13:11.590   930  3827 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-04 00:13:11.590   930  5858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-04 00:13:11.591   930  5858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
11-04 00:13:11.591   930  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-04 00:13:11.592   930  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-04 00:13:11.595   599   599 E Parcel  : Reading a NULL string not supported here.
11-04 00:13:11.598   930   930 D RttService: SCAN_AVAILABLE : 1
11-04 00:13:11.599   930  3072 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-04 00:13:11.599   930  3021 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-04 00:13:11.600  3758  3888 W QCNEJ   : |CORE| network lost: 101
11-04 00:13:11.601   930  3019 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-04 00:13:11.601  3758  3888 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-04 00:13:11.603   930  5858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-04 00:13:11.604   930  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 00:13:11.611   930  5861 D DhcpClient: Receive thread stopped
,11-04 00:13:11.623   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 00:13:11.645   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 00:13:11.646   930  3021 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-04 00:13:11.646   509   923 D CommandListener: Clearing all IP addresses on wlan0
11-04 00:13:11.646   930  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 00:13:11.649   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-04 00:13:11.650  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:11.650  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 00:13:11.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:11.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:11.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 00:13:11.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 00:13:11.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 00:13:11.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 00:13:11.650  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 00:13:11.650  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:11.650  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 00:13:11.651   930  3019 D DhcpClient: doQuit
11-04 00:13:11.651   930  3019 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 00:13:11.651   930  5860 D DhcpClient: onQuitting
11-04 00:13:11.652  5846  5846 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-04 00:13:11.656  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 00:13:11.656  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 00:13:11.656  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:11.656  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:11.656  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 00:13:11.656  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 00:13:11.656  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 00:13:11.656  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 00:13:11.656  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 00:13:11.656  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:11.656  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 00:13:11.662  3978  3978 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-04 00:13:11.663  5846  5846 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 00:13:11.665  4015  4015 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 00:13:11.666  5846  5846 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-04 00:13:11.669  4015  4015 D SystemUpdateService: onCreate
,11-04 00:13:11.673  4015  4015 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 00:13:11.677  4015  5886 I SystemUpdateService: active receiver: enabled
,11-04 00:13:11.682  4015  4015 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 00:13:11.686  4015  4241 I iu.UploadsManager: num queued entries: 0
,11-04 00:13:11.686  4015  4241 I iu.UploadsManager: num updated entries: 0
11-04 00:13:11.687  4015  4241 I iu.SyncManager: NEXT; no task
,11-04 00:13:11.690  4015  4015 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 00:13:11.691  5846  5846 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 00:13:11.691  4015  4015 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 00:13:11.694  5799  5799 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-04 00:13:11.698  5799  5799 D SprintDMHelper: simOperator: 
11-04 00:13:11.698  5799  5799 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 00:13:11.703   509   923 E Netd    : netlink response contains error (No such file or directory)
,11-04 00:13:11.704   930  3021 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-04 00:13:11.704   930  3021 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-04 00:13:11.705  5846  5846 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-04 00:13:11.709  4015  5886 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 00:13:11.711  4546  4546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 00:13:11.711   930  3019 D wifi    : In wifi stop Hal
,11-04 00:13:11.711   930  3019 D wifi    : halHandle = 0x7f74fd1b80, mVM = 0x7f9160d140, mCls = 0x193e
11-04 00:13:11.711   930  5844 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 00:13:11.711   930  5844 D WifiHAL : Got a signal to exit!!!
,11-04 00:13:11.711   930  5844 I WifiHAL : Exit wifi_event_loop
11-04 00:13:11.712   930  3019 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-04 00:13:11.713  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 00:13:11.712   930  3019 E WifiHAL : Event processing terminated
11-04 00:13:11.713   930  3019 D wifi    : In wifi cleaned up handler
11-04 00:13:11.713   930  3019 I WifiHAL : Internal cleanup completed
11-04 00:13:11.714  3724  4218 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 00:13:11.724  4015  5886 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-04 00:13:11.724  4015  5886 I SystemUpdateService: now status is 0 (complete)
11-04 00:13:11.724  4015  5886 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 00:13:11.724  4015  5886 I SystemUpdateService: file has been verified
11-04 00:13:11.724  4015  5886 I SystemUpdateService: OTA package size = 21989297
,11-04 00:13:11.734   930  5844 D wifi    : set interface wlan0 flags (DOWN)
,11-04 00:13:11.735   930  3019 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 00:13:11.735  4015  5886 I SystemUpdateService: showing system update notification
,11-04 00:13:11.743   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 00:13:11.746  4015  4015 D SystemUpdateService: onDestroy
,11-04 00:13:11.795   509   923 E Netd    : netlink response contains error (No such file or directory)
,11-04 00:13:11.940   930   947 D Tethering: InitialState.processMessage what=4
,11-04 00:13:11.946   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 00:13:11.965   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:12.409   930  3021 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-04 00:13:12.966   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:13.967   602   602 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-04 00:13:16.602   930   947 I ActivityManager: Start proc 5899:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 00:13:16.685  5899  5899 D AdapterServiceConfig: Adding HeadsetService
11-04 00:13:16.685  5899  5899 D AdapterServiceConfig: Adding A2dpService
11-04 00:13:16.685  5899  5899 D AdapterServiceConfig: Adding HidService
11-04 00:13:16.685  5899  5899 D AdapterServiceConfig: Adding HealthService
11-04 00:13:16.686  5899  5899 D AdapterServiceConfig: Adding PanService
11-04 00:13:16.686  5899  5899 D AdapterServiceConfig: Adding GattService
11-04 00:13:16.686  5899  5899 D AdapterServiceConfig: Adding BluetoothMapService
11-04 00:13:16.686  5899  5899 D AdapterServiceConfig: Adding SapService
,11-04 00:13:16.697   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7a2f988:true
,11-04 00:13:16.697  5899  5899 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 00:13:16.701  5899  5899 I bt_bluedroid: init
,11-04 00:13:16.701  5899  5911 I BluetoothAdapterState: Entering OffState
,11-04 00:13:16.703  5899  5912 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 00:13:16.703  5899  5912 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 00:13:16.703  5899  5912 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 00:13:16.703  5899  5912 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-04 00:13:16.704  5899  5899 I bt_bluedroid: get_profile_interface socket
,11-04 00:13:16.706  5899  5899 I bt_bluedroid: get_profile_interface sdp
,11-04 00:13:16.706  5899  5915 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-04 00:13:16.707  5899  5915 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 00:13:16.712  5899  5910 I bt_bluedroid: config_hci_snoop_log
,11-04 00:13:16.713   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 00:13:16.718  5899  5911 D BluetoothAdapterState: Current state: OFF, message: 0
,11-04 00:13:16.718  5899  5911 D BluetoothAdapterProperties: Setting state to 14
11-04 00:13:16.718  5899  5911 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-04 00:13:16.719  5899  5911 D BluetoothBondStateMachine: make
,11-04 00:13:16.721  5899  5916 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 00:13:16.724  5899  5911 I BluetoothAdapterState: Entering PendingCommandState
,11-04 00:13:16.725  5899  5899 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 00:13:16.727  5899  5899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
11-04 00:13:16.727  5899  5899 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 00:13:16.728  5899  5899 D BtGatt.GattService: Received start request. Starting profile...
11-04 00:13:16.728  5899  5899 D BtGatt.GattService: start()
11-04 00:13:16.728  5899  5899 I bt_bluedroid: get_profile_interface gatt
11-04 00:13:16.729  5899  5899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
11-04 00:13:16.729  5899  5899 D BtGatt.AdvertiseManager: advertise manager created
,11-04 00:13:16.734  5899  5899 V BluetoothAdapterState: isTurningOff()=false
,11-04 00:13:16.734  5899  5899 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:16.734  5899  5899 V BluetoothAdapterState: isBleTurningOn()=true
11-04 00:13:16.735  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 00:13:16.735  5899  5911 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 00:13:16.737  5899  5911 I bt_bluedroid: bt_bluedroid
,11-04 00:13:16.737  5899  5912 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-04 00:13:16.737  5899  5912 I bt_hci  : start_up
,11-04 00:13:16.743  5899  5912 I bt_vendor: alloc value 0xf3ffb871
,11-04 00:13:16.743  5899  5912 I bt_vendor: init
11-04 00:13:16.743  5899  5912 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 00:13:16.743  5899  5912 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 00:13:16.855  5899  5912 D bt_hci  : start_up starting async portion
,11-04 00:13:16.855  5899  5919 I bt_hci  : event_finish_startup
,11-04 00:13:16.856  5899  5919 I bt_hci_h4: hal_open
11-04 00:13:16.856  5899  5919 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 00:13:16.859  5899  5919 I bt_userial_vendor: device fd = 54 open
,11-04 00:13:16.854  5920  5920 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 00:13:16.873  5899  5919 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 00:13:16.876  5899  5919 D bt_hwcfg: Chipset BCM4358A3
,11-04 00:13:16.876  5899  5919 D bt_hwcfg: Target name = [BCM4358A3]
11-04 00:13:16.876  5899  5919 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 00:13:17.284  5899  5919 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-04 00:13:17.284  5899  5919 D bt_hwcfg: Settlement delay -- 100 ms
,11-04 00:13:17.284  5899  5919 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 00:13:17.418  5899  5919 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 00:13:17.419  5899  5919 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-04 00:13:17.421  5899  5919 I bt_hwcfg: vendor lib fwcfg completed
11-04 00:13:17.421  5899  5919 I bt_vendor: firmware callback
11-04 00:13:17.421  5899  5919 I bt_hci  : firmware_config_callback
,11-04 00:13:17.429  5899  5922 I bt_btu  : btu_task pending for preload complete event
,11-04 00:13:17.430  5899  5922 I bt_btu_task: Bluetooth chip preload is complete
11-04 00:13:17.430  5899  5922 I bt_btu  : btu_task received preload complete event
,11-04 00:13:17.436  5899  5922 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 00:13:17.436  5899  5922 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 00:13:17.436  5899  5922 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 00:13:17.436  5899  5922 I         : BTE_InitTraceLevels -- TRC_AVDT
11-04 00:13:17.437  5899  5922 I         : BTE_InitTraceLevels -- TRC_AVRC
11-04 00:13:17.437  5899  5922 I         : BTE_InitTraceLevels -- TRC_A2D
,11-04 00:13:17.437  5899  5922 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 00:13:17.437  5899  5922 I         : BTE_InitTraceLevels -- TRC_BTM
11-04 00:13:17.437  5899  5922 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 00:13:17.437  5899  5922 I         : BTE_InitTraceLevels -- TRC_PAN
,11-04 00:13:17.437  5899  5922 I         : BTE_InitTraceLevels -- TRC_SDP
11-04 00:13:17.437  5899  5922 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 00:13:17.437  5899  5922 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 00:13:17.438  5899  5922 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-04 00:13:17.438  5899  5922 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 00:13:17.522  5899  5922 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f79549
11-04 00:13:17.523  5899  5922 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f79549 
,11-04 00:13:17.539  5899  5915 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 00:13:17.540  5899  5915 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 00:13:17.541  5899  5915 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 00:13:17.543  5899  5915 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 00:13:17.547  5899  5915 D BluetoothAdapterProperties: Scan Mode:20
11-04 00:13:17.547  5899  5915 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-04 00:13:17.547  5899  5915 D bt_hci  : do_postload posting postload work item
11-04 00:13:17.548  5899  5919 I bt_hci  : event_postload
11-04 00:13:17.548  5899  5919 I bt_vendor: sco_config_cb
11-04 00:13:17.548  5899  5919 I bt_hci  : sco_config_callback postload finished.
11-04 00:13:17.550  5899  5915 D bt_bte_conf: Device ID record 1 : primary
11-04 00:13:17.551  5899  5915 D bt_bte_conf:   vendorId            = 000f
,11-04 00:13:17.551  5899  5915 D bt_bte_conf:   vendorIdSource      = 0001
11-04 00:13:17.551  5899  5915 D bt_bte_conf:   product             = 1200
11-04 00:13:17.551  5899  5915 D bt_bte_conf:   version             = 1436
11-04 00:13:17.551  5899  5915 D bt_bte_conf:   clientExecutableURL = 
,11-04 00:13:17.551  5899  5915 D bt_bte_conf:   serviceDescription  = 
11-04 00:13:17.551  5899  5915 D bt_bte_conf:   documentationURL    = 
11-04 00:13:17.552  5899  5915 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-04 00:13:17.552  5899  5912 D bt_stack_manager: event_start_up_stack finished
,11-04 00:13:17.552  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 00:13:17.553  5899  5911 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 00:13:17.553  5899  5911 D BluetoothAdapterProperties: Setting state to 15
11-04 00:13:17.553  5899  5911 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 00:13:17.554  5899  5911 I BluetoothAdapterState: Entering BleOnState
,11-04 00:13:17.562  5899  5911 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-04 00:13:17.562  5899  5911 D BluetoothAdapterProperties: Setting state to 11
11-04 00:13:17.562  5899  5911 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-04 00:13:17.564  5899  5919 I bt_vendor: low_power_mode_cb
,11-04 00:13:17.570  5899  5899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
11-04 00:13:17.571  5899  5899 D HeadsetService: Received start request. Starting profile...
,11-04 00:13:17.574  5899  5899 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 00:13:17.574  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 00:13:17.575  5899  5899 D HeadsetStateMachine: make
,11-04 00:13:17.587  5899  5899 D HeadsetStateMachine: max_hf_connections = 1
11-04 00:13:17.587  5899  5899 I bt_bluedroid: get_profile_interface handsfree
,11-04 00:13:17.587  5899  5915 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 00:13:17.587  5899  5915 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-04 00:13:17.590  5899  5899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
11-04 00:13:17.590  5899  5911 I BluetoothAdapterState: Entering PendingCommandState
11-04 00:13:17.591  5899  5899 D A2dpService: Received start request. Starting profile...
,11-04 00:13:17.591  5899  5899 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-04 00:13:17.592  5899  5899 I bt_bluedroid: get_profile_interface avrcp
,11-04 00:13:17.598  5899  5899 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 00:13:17.598  5899  5899 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 00:13:17.598  5899  5899 D A2dpStateMachine: make
,11-04 00:13:17.599  5899  5899 I bt_bluedroid: get_profile_interface a2dp
,11-04 00:13:17.600  5899  5915 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-04 00:13:17.601  5899  5930 D A2dpStateMachine: Enter Disconnected: -2
,11-04 00:13:17.603  5899  5899 I BluetoothHidServiceJni: classInitNative: succeeds
,11-04 00:13:17.604  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 00:13:17.604  5899  5899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
,11-04 00:13:17.607  5739  5739 D BluetoothInputDevice: Proxy object connected
,11-04 00:13:17.607  5899  5899 D HidService: Received start request. Starting profile...
11-04 00:13:17.607  5899  5899 I bt_bluedroid: get_profile_interface hidhost
11-04 00:13:17.607  5899  5915 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f5a56d
11-04 00:13:17.607  5899  5899 D HidService: setHidService(): set to: null
11-04 00:13:17.607  5739  5739 D HidProfile: Bluetooth service connected
11-04 00:13:17.607  5899  5915 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 00:13:17.607  5899  5899 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 00:13:17.608  5899  5899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
11-04 00:13:17.608  5899  5899 D HealthService: Received start request. Starting profile...
,11-04 00:13:17.610  5899  5899 I bt_bluedroid: get_profile_interface health
,11-04 00:13:17.610  5899  5899 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-04 00:13:17.611  5899  5899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
,11-04 00:13:17.612  5739  5739 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 00:13:17.613  5739  5739 D PanProfile: Bluetooth service connected
,11-04 00:13:17.616  5899  5899 D PanService: Received start request. Starting profile...
11-04 00:13:17.616  5899  5899 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 00:13:17.616  5899  5899 I bt_bluedroid: get_profile_interface pan
11-04 00:13:17.616  5899  5915 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-04 00:13:17.618  5899  5899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
,11-04 00:13:17.619  5899  5899 D BluetoothMapService: Received start request. Starting profile...
,11-04 00:13:17.619  5899  5899 D BluetoothMapService: start()
11-04 00:13:17.619  5739  5739 D BluetoothMap: Proxy object connected
11-04 00:13:17.620  5739  5739 D MapProfile: Bluetooth service connected
11-04 00:13:17.620  5739  5739 D BluetoothMap: getConnectedDevices()
11-04 00:13:17.620  5739  5739 D BluetoothMap: Bluetooth is Not enabled
,11-04 00:13:17.622  5899  5899 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-04 00:13:17.622  5899  5899 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-04 00:13:17.623  5899  5899 D BluetoothMapAppObserver: createReceiver()
11-04 00:13:17.624  5899  5899 D BluetoothMapAppObserver: initObservers()
11-04 00:13:17.624  5899  5899 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 00:13:17.630  5899  5899 V SapService: SapBinder()
11-04 00:13:17.630  5899  5899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
,11-04 00:13:17.630  5899  5899 D SapService: Received start request. Starting profile...
11-04 00:13:17.630  5899  5899 V SapService: start()
,11-04 00:13:17.632  5899  5899 V BluetoothAdapterState: isTurningOff()=false
,11-04 00:13:17.632  5899  5899 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:17.632  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:17.632  5899  5928 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 00:13:17.632  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:17.632  5899  5899 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:17.632  5899  5899 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:17.632  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:17.632  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isTurningOff()=false
,11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 00:13:17.633  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:17.634  5899  5899 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:17.634  5899  5899 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:17.634  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:17.634  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:17.634  5899  5911 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 00:13:17.634  5899  5911 D BluetoothAdapterProperties: ScanMode =  20
11-04 00:13:17.634  5899  5911 D BluetoothAdapterProperties: State =  11
11-04 00:13:17.635  5899  5911 D BluetoothAdapterProperties: Setting state to 12
11-04 00:13:17.635  5899  5911 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-04 00:13:17.635  3123  3139 D BluetoothMap: onBluetoothStateChange: up=true
11-04 00:13:17.636  5899  5911 I BluetoothAdapterState: Entering OnState
11-04 00:13:17.638  5899  5915 D BluetoothAdapterProperties: Scan Mode:21
11-04 00:13:17.638  5899  5915 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 00:13:17.638  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 00:13:17.639  3123  3123 D BluetoothMap: Proxy object connected
11-04 00:13:17.639  3123  3123 D MapProfile: Bluetooth service connected
11-04 00:13:17.639  3123  3123 D BluetoothMap: getConnectedDevices()
,11-04 00:13:17.639  5739  5751 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-04 00:13:17.639   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 00:13:17.639  3123  3878 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 00:13:17.641  3123  3140 D BluetoothPan: onBluetoothStateChange on: true
11-04 00:13:17.642  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 00:13:17.642  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:17.642  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:17.642  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 00:13:17.642  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 00:13:17.642  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 00:13:17.642  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 00:13:17.642  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 00:13:17.643  3123  3123 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 00:13:17.643  3123  3878 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 00:13:17.643  3123  3123 D PanProfile: Bluetooth service connected
,11-04 00:13:17.644  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 00:13:17.644  3796  4046 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 00:13:17.645  5739  5752 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 00:13:17.645  3123  3123 D BluetoothA2dp: Proxy object connected
11-04 00:13:17.646  3123  3139 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 00:13:17.646   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 00:13:17.647   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 00:13:17.647   930   930 D BluetoothA2dp: Proxy object connected
11-04 00:13:17.647  5739  5751 D BluetoothMap: onBluetoothStateChange: up=true
11-04 00:13:17.647   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 00:13:17.647  5739  5752 D BluetoothPan: onBluetoothStateChange on: true
11-04 00:13:17.648  3123  3878 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 00:13:17.648  5899  5899 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 00:13:17.649  5899  5899 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 00:13:17.649  3123  3123 D BluetoothInputDevice: Proxy object connected
11-04 00:13:17.649  3123  3123 D HidProfile: Bluetooth service connected
11-04 00:13:17.650  5899  5899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 00:13:17.650   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-04 00:13:17.651  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-04 00:13:17.653  5739  5739 D LocalBluetoothProfileManager: Adding local A2DP profile
11-04 00:13:17.653  5899  5899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 00:13:17.653  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 00:13:17.654  5899  5899 D ObexServerSockets: Succeed to create listening sockets 
11-04 00:13:17.655  5899  5899 D ObexServerSockets0: startAccept()
11-04 00:13:17.655  5899  5899 D ObexServerSockets0: prepareForNewConnect()
11-04 00:13:17.656  5739  5739 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-04 00:13:17.657  5899  5899 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 00:13:17.657  5899  5899 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 00:13:17.658  5899  5899 D BluetoothMapService: onReceive
,11-04 00:13:17.658  5899  5936 D ObexServerSockets0: Accepting socket connection...
11-04 00:13:17.658  5899  5899 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 00:13:17.658  5899  5899 D BluetoothMapService: STATE_ON
11-04 00:13:17.659  5899  5937 D ObexServerSockets0: Accepting socket connection...
11-04 00:13:17.660  5899  5938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 00:13:17.662  5899  5938 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 00:13:17.662  5899  5938 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-04 00:13:17.664  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 00:13:17.666  5739  5739 D BluetoothA2dp: Proxy object connected
,11-04 00:13:17.671  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 00:13:17.676  5739  5739 D DockEventReceiver: finishStartingService: stopping service
,11-04 00:13:17.679  3123  3123 D BluetoothPbap: Proxy object connected
11-04 00:13:17.679  3123  3123 D PbapServerProfile: Bluetooth service connected
11-04 00:13:17.679  5739  5739 D BluetoothPbap: Proxy object connected
11-04 00:13:17.679  5739  5739 D PbapServerProfile: Bluetooth service connected
,11-04 00:13:17.684  5899  5899 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 00:13:17.684  5899  5899 D ObexServerSockets0: prepareForNewConnect()
,11-04 00:13:17.686  5899  5942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 00:13:17.701  5899  5946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 00:13:17.702  5899  5946 I BtOppRfcommListener: Accept thread started.
,11-04 00:13:17.741  3796  3825 D BluetoothHeadset: Proxy object connected
,11-04 00:13:17.741   930   930 D BluetoothHeadset: Proxy object connected
11-04 00:13:17.741   930   930 D BluetoothHeadset: Proxy object connected
11-04 00:13:17.741   930   930 D BluetoothHeadset: Proxy object connected
11-04 00:13:17.741  3123  3878 D BluetoothHeadset: Proxy object connected
,11-04 00:13:17.741  3123  3123 D HeadsetProfile: Bluetooth service connected
,11-04 00:13:17.745  3796  4049 D BluetoothHeadset: Proxy object connected
,11-04 00:13:17.747  3123  3140 D BluetoothHeadset: Proxy object connected
,11-04 00:13:17.747  3123  3123 D HeadsetProfile: Bluetooth service connected
11-04 00:13:17.747   930   947 D BluetoothHeadset: Proxy object connected
,11-04 00:13:17.748   930   947 D BluetoothHeadset: Proxy object connected
,11-04 00:13:17.759  5739  5752 D BluetoothHeadset: Proxy object connected
,11-04 00:13:17.759  5739  5739 D HeadsetProfile: Bluetooth service connected
,11-04 00:13:18.968   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:19.356   930  3021 D ConnectivityService: handlePromptUnvalidated 101
,11-04 00:13:19.968   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:20.007  3675  3862 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-04 00:13:20.008  3675  3862 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-04 00:13:20.039  3620  3620 I ConfigService: onCreate
,11-04 00:13:20.969   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:21.581  5899  5911 D BluetoothAdapterState: Current state: ON, message: 23
11-04 00:13:21.582  5899  5911 D BluetoothAdapterProperties: Setting state to 13
,11-04 00:13:21.582  5899  5911 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-04 00:13:21.584  5899  5911 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 00:13:21.585  5899  5911 I BluetoothAdapterState: Entering PendingCommandState
11-04 00:13:21.587  5899  5915 D BluetoothAdapterProperties: Scan Mode:20
,11-04 00:13:21.588  5899  5911 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-04 00:13:21.593  5899  5899 D BluetoothMapService: onReceive
11-04 00:13:21.593  5899  5899 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 00:13:21.594  5899  5899 D BluetoothMapService: STATE_TURNING_OFF
11-04 00:13:21.594  5899  5899 D BluetoothMapService: MAP Service closeService in
11-04 00:13:21.594  5899  5899 D BluetoothMapMasInstance0: MAP Service shutdown
11-04 00:13:21.595  5899  5899 D ObexServerSockets0: shutdown(block = true)
11-04 00:13:21.596  5899  5936 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-04 00:13:21.597  5899  5899 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 00:13:21.597  5899  5899 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 00:13:21.599  5899  5937 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-04 00:13:21.601  5899  5924 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 00:13:21.605  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:21.605  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 00:13:21.605  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:21.605  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:21.605  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 00:13:21.605  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 00:13:21.605  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 00:13:21.605  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 00:13:21.605  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 00:13:21.606  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 00:13:21.606  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 00:13:21.607  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 00:13:21.608  5899  5899 I BtOppRfcommListener: stopping Accept Thread
,11-04 00:13:21.609  5899  5946 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-04 00:13:21.609  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 00:13:21.609  5899  5946 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-04 00:13:21.613  5899  5899 D HeadsetService: Received stop request...Stopping profile...
,11-04 00:13:21.616  3796  3826 D BluetoothHeadset: Proxy object disconnected
,11-04 00:13:21.616   930   930 D BluetoothHeadset: Proxy object disconnected
11-04 00:13:21.616   930   930 D BluetoothHeadset: Proxy object disconnected
11-04 00:13:21.616   930   930 D BluetoothHeadset: Proxy object disconnected
11-04 00:13:21.616  5899  5899 D A2dpService: Received stop request...Stopping profile...
11-04 00:13:21.616  5739  5751 D BluetoothHeadset: Proxy object disconnected
,11-04 00:13:21.617  5899  5930 D A2dpStateMachine: Exit Disconnected: -1
11-04 00:13:21.617  3123  3139 D BluetoothHeadset: Proxy object disconnected
11-04 00:13:21.618  5899  5899 D HidService: Received stop request...Stopping profile...
11-04 00:13:21.619  5899  5899 D HidService: Stopping Bluetooth HidService
,11-04 00:13:21.619   930   930 D BluetoothA2dp: Proxy object disconnected
11-04 00:13:21.620  5899  5899 D HealthService: Received stop request...Stopping profile...
11-04 00:13:21.621  5739  5739 D DockEventReceiver: finishStartingService: stopping service
11-04 00:13:21.623  5739  5739 D HeadsetProfile: Bluetooth service disconnected
11-04 00:13:21.623  5739  5739 D BluetoothA2dp: Proxy object disconnected
11-04 00:13:21.624  5739  5739 D BluetoothInputDevice: Proxy object disconnected
11-04 00:13:21.624  5739  5739 D HidProfile: Bluetooth service disconnected
11-04 00:13:21.625  5899  5899 D PanService: Received stop request...Stopping profile...
11-04 00:13:21.626  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 00:13:21.626  5739  5739 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 00:13:21.626  5739  5739 D PanProfile: Bluetooth service disconnected
11-04 00:13:21.626  5899  5899 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:21.626  5899  5899 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:21.627  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:21.627  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 00:13:21.628  5899  5899 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 00:13:21.628  5899  5899 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 00:13:21.629  5899  5922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 00:13:21.629  5899  5922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 00:13:21.629  5899  5899 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:21.629  5899  5922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 00:13:21.629  5899  5899 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:21.629  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:21.629  5899  5915 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 00:13:21.629  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:21.629  5899  5915 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-04 00:13:21.630  5899  5915 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-04 00:13:21.630  5899  5922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 00:13:21.630  5899  5899 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:21.630  5899  5922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 00:13:21.630  5899  5899 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:21.630  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:21.630  5899  5922 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 00:13:21.630  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:21.630  5899  5922 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-04 00:13:21.630  5899  5922 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 00:13:21.631  5899  5922 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 00:13:21.631  5899  5899 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 00:13:21.631  5899  5899 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 00:13:21.631  5899  5915 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 00:13:21.631  5899  5899 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:21.631  5899  5899 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:21.631  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:21.631  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:21.631  5899  5899 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-04 00:13:21.632  5899  5915 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 00:13:21.632  3123  3123 D HeadsetProfile: Bluetooth service disconnected
11-04 00:13:21.632  3123  3123 D BluetoothA2dp: Proxy object disconnected
11-04 00:13:21.633  3123  3123 D BluetoothInputDevice: Proxy object disconnected
11-04 00:13:21.633  3123  3123 D HidProfile: Bluetooth service disconnected
11-04 00:13:21.633  3123  3123 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 00:13:21.633  3123  3123 D PanProfile: Bluetooth service disconnected
11-04 00:13:21.635  5899  5899 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 00:13:21.636  5899  5899 D BluetoothMapService: Received stop request...Stopping profile...
11-04 00:13:21.636  5899  5899 D BluetoothMapService: stop()
11-04 00:13:21.636  5899  5899 D BluetoothMapAppObserver: deinitObservers()
11-04 00:13:21.636  5899  5899 D BluetoothMapAppObserver: removeReceiver()
11-04 00:13:21.638  3123  3123 D BluetoothMap: Proxy object disconnected
11-04 00:13:21.638  3123  3123 D MapProfile: Bluetooth service disconnected
,11-04 00:13:21.640  5899  5899 D SapService: Received stop request...Stopping profile...
11-04 00:13:21.640  3123  3123 D BluetoothPbap: Proxy object disconnected
11-04 00:13:21.640  5899  5899 V SapService: stop()
11-04 00:13:21.640  3123  3123 D PbapServerProfile: Bluetooth service disconnected
11-04 00:13:21.641  5899  5899 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:21.641  5899  5899 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:21.641  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 00:13:21.641  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:21.641  5899  5899 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 00:13:21.642  5899  5899 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 00:13:21.642  5899  5899 D BluetoothMapService: MAP Service closeService in
11-04 00:13:21.643  5899  5899 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:21.643  5899  5899 V BluetoothAdapterState: isTurningOn()=false
,11-04 00:13:21.643  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:21.643  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:21.643  5899  5899 D BluetoothMapService: cleanup()
11-04 00:13:21.643  5899  5899 D BluetoothMapService: MAP Service closeService in
11-04 00:13:21.645  5899  5899 V BluetoothAdapterState: isTurningOff()=true
11-04 00:13:21.645  5899  5899 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:21.645  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:21.645  5899  5899 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:21.645  5899  5911 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-04 00:13:21.645  5899  5911 D BluetoothAdapterProperties: Setting state to 15
11-04 00:13:21.645  5899  5911 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 00:13:21.646  5899  5911 I BluetoothAdapterState: Entering BleOnState
11-04 00:13:21.646  3123  3139 D BluetoothMap: onBluetoothStateChange: up=false
11-04 00:13:21.646  5739  5739 D BluetoothMap: Proxy object disconnected
11-04 00:13:21.646  5739  5739 D MapProfile: Bluetooth service disconnected
11-04 00:13:21.646  5739  5739 D BluetoothPbap: Proxy object disconnected
11-04 00:13:21.646  5739  5739 D PbapServerProfile: Bluetooth service disconnected
,11-04 00:13:21.647  5739  5752 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 00:13:21.647   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 00:13:21.648  3123  3140 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 00:13:21.650  3123  3139 D BluetoothPan: onBluetoothStateChange on: false
11-04 00:13:21.650  5739  5751 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-04 00:13:21.651  5739  5752 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 00:13:21.651  3123  3878 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 00:13:21.652  3796  4046 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 00:13:21.652  5739  5751 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 00:13:21.653  3123  3140 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 00:13:21.653   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 00:13:21.653   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 00:13:21.653  5739  5752 D BluetoothMap: onBluetoothStateChange: up=false
11-04 00:13:21.653   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 00:13:21.653  5739  5751 D BluetoothPan: onBluetoothStateChange on: false
11-04 00:13:21.654  3123  3139 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 00:13:21.655  5899  5911 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-04 00:13:21.655  5899  5911 D BluetoothAdapterProperties: Setting state to 16
11-04 00:13:21.655  5899  5911 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-04 00:13:21.656  5899  5911 D BluetoothAdapterProperties: onBleDisable
11-04 00:13:21.656  5899  5911 I BluetoothAdapterState: Entering PendingCommandState
11-04 00:13:21.656  5899  5912 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 00:13:21.658  5899  5922 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 00:13:21.658  5899  5922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 00:13:21.659  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 00:13:21.660  5899  5915 D BluetoothAdapterProperties: Scan Mode:20
11-04 00:13:21.660  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 00:13:21.663  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 00:13:21.667  5739  5739 D DockEventReceiver: finishStartingService: stopping service
,11-04 00:13:21.668  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 00:13:21.878  5899  5915 I bt_hci  : shut_down
,11-04 00:13:21.888  5899  5919 D bt_hwcfg: hw_epilog_process
,11-04 00:13:21.889  5899  5919 I bt_vendor: low_power_mode_cb
,11-04 00:13:21.892  5899  5919 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-04 00:13:21.892  5899  5919 I bt_vendor: epilog_cb
11-04 00:13:21.892  5899  5919 I bt_hci  : epilog_finished_callback
,11-04 00:13:21.896  5899  5915 I bt_hci_h4: hal_close
,11-04 00:13:21.897  5899  5915 I bt_userial_vendor: device fd = 54 close
,11-04 00:13:21.970   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:22.022  5899  5912 D bt_stack_manager: event_shut_down_stack finished.
,11-04 00:13:22.023  5899  5911 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-04 00:13:22.027  5899  5911 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-04 00:13:22.027  5899  5899 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 00:13:22.029  5899  5899 D BtGatt.GattService: Received stop request...Stopping profile...
,11-04 00:13:22.029  5899  5899 D BtGatt.GattService: stop()
11-04 00:13:22.029  5899  5899 D BtGatt.AdvertiseManager: advertise clients cleared
,11-04 00:13:22.034  5899  5899 V BluetoothAdapterState: isTurningOff()=false
,11-04 00:13:22.034  5899  5899 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:22.035  5899  5899 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 00:13:22.035  5899  5899 V BluetoothAdapterState: isBleTurningOff()=true
11-04 00:13:22.035  5899  5911 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-04 00:13:22.037  5899  5911 D BluetoothAdapterProperties: Setting state to 10
11-04 00:13:22.037  5899  5911 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 00:13:22.039  5899  5911 I BluetoothAdapterState: Entering OffState
,11-04 00:13:22.039   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-04 00:13:22.052  5899  5899 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-04 00:13:22.052  5899  5899 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 00:13:22.052  5899  5899 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-04 00:13:22.054  5899  5912 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 00:13:22.061  5899  5899 I art     : System.exit called, status: 0
,11-04 00:13:22.061  5899  5899 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 00:13:22.089   930  4043 I ActivityManager: Process com.android.bluetooth (pid 5899) has died
,11-04 00:13:22.971   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:23.972   602   602 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-04 00:13:25.074  3620  3620 I ConfigService: onDestroy
,11-04 00:13:26.579  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 00:13:26.580  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 00:13:26.585  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:13:26.585  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9163cf1 removed from the list
,11-04 00:13:26.586  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 00:13:26.588  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 00:13:26.589  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a2b3a44 added. We now have 4 listener(s)
11-04 00:13:26.589  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 00:13:26.591  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:13:26.592  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a2b3a44 removed from the list
11-04 00:13:26.592  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 00:13:26.594  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:13:26.594  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c0b72d added. We now have 4 listener(s)
11-04 00:13:26.594  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 00:13:31.604  5679  5727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 00:13:31.638   930   947 I ActivityManager: Start proc 5956:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 00:13:31.723  5956  5956 D AdapterServiceConfig: Adding HeadsetService
,11-04 00:13:31.723  5956  5956 D AdapterServiceConfig: Adding A2dpService
,11-04 00:13:31.724  5956  5956 D AdapterServiceConfig: Adding HidService
11-04 00:13:31.724  5956  5956 D AdapterServiceConfig: Adding HealthService
,11-04 00:13:31.724  5956  5956 D AdapterServiceConfig: Adding PanService
11-04 00:13:31.724  5956  5956 D AdapterServiceConfig: Adding GattService
,11-04 00:13:31.724  5956  5956 D AdapterServiceConfig: Adding BluetoothMapService
11-04 00:13:31.724  5956  5956 D AdapterServiceConfig: Adding SapService
,11-04 00:13:31.736   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8be1e1d:true
,11-04 00:13:31.736  5956  5956 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 00:13:31.739  5956  5956 I bt_bluedroid: init
,11-04 00:13:31.740  5956  5968 I BluetoothAdapterState: Entering OffState
,11-04 00:13:31.743  5956  5969 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 00:13:31.743  5956  5969 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-04 00:13:31.743  5956  5969 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 00:13:31.743  5956  5969 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-04 00:13:31.744  5956  5956 I bt_bluedroid: get_profile_interface socket
,11-04 00:13:31.745  5956  5972 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 00:13:31.745  5956  5956 I bt_bluedroid: get_profile_interface sdp
11-04 00:13:31.747  5956  5972 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 00:13:31.751  5956  5967 I bt_bluedroid: config_hci_snoop_log
,11-04 00:13:31.752   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 00:13:31.756  5956  5968 D BluetoothAdapterState: Current state: OFF, message: 0
11-04 00:13:31.756  5956  5968 D BluetoothAdapterProperties: Setting state to 14
,11-04 00:13:31.756  5956  5968 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-04 00:13:31.767  5956  5968 D BluetoothBondStateMachine: make
,11-04 00:13:31.769  5956  5973 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 00:13:31.773  5956  5956 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 00:13:31.775  5956  5956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
,11-04 00:13:31.775  5956  5968 I BluetoothAdapterState: Entering PendingCommandState
11-04 00:13:31.775  5956  5956 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 00:13:31.776  5956  5956 D BtGatt.GattService: Received start request. Starting profile...
,11-04 00:13:31.776  5956  5956 D BtGatt.GattService: start()
11-04 00:13:31.776  5956  5956 I bt_bluedroid: get_profile_interface gatt
,11-04 00:13:31.777  5956  5956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
11-04 00:13:31.777  5956  5956 D BtGatt.AdvertiseManager: advertise manager created
,11-04 00:13:31.783  5956  5956 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:31.783  5956  5956 V BluetoothAdapterState: isTurningOn()=false
11-04 00:13:31.783  5956  5956 V BluetoothAdapterState: isBleTurningOn()=true
11-04 00:13:31.783  5956  5956 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:31.783  5956  5968 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 00:13:31.784  5956  5968 I bt_bluedroid: bt_bluedroid
,11-04 00:13:31.785  5956  5969 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-04 00:13:31.785  5956  5969 I bt_hci  : start_up
,11-04 00:13:31.790  5956  5969 I bt_vendor: alloc value 0xf3ffb871
11-04 00:13:31.790  5956  5969 I bt_vendor: init
,11-04 00:13:31.790  5956  5969 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 00:13:31.790  5956  5969 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 00:13:31.899  5956  5969 D bt_hci  : start_up starting async portion
,11-04 00:13:31.899  5956  5976 I bt_hci  : event_finish_startup
,11-04 00:13:31.899  5956  5976 I bt_hci_h4: hal_open
,11-04 00:13:31.899  5956  5976 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 00:13:31.897  5977  5977 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 00:13:31.903  5956  5976 I bt_userial_vendor: device fd = 54 open
,11-04 00:13:31.917  5956  5976 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 00:13:31.920  5956  5976 D bt_hwcfg: Chipset BCM4358A3
,11-04 00:13:31.920  5956  5976 D bt_hwcfg: Target name = [BCM4358A3]
11-04 00:13:31.920  5956  5976 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 00:13:32.433  5956  5976 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 00:13:32.434  5956  5976 D bt_hwcfg: Settlement delay -- 100 ms
11-04 00:13:32.434  5956  5976 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 00:13:32.568  5956  5976 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 00:13:32.569  5956  5976 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-04 00:13:32.571  5956  5976 I bt_hwcfg: vendor lib fwcfg completed
,11-04 00:13:32.571  5956  5976 I bt_vendor: firmware callback
11-04 00:13:32.571  5956  5976 I bt_hci  : firmware_config_callback
,11-04 00:13:32.582  5956  5979 I bt_btu  : btu_task pending for preload complete event
,11-04 00:13:32.583  5956  5979 I bt_btu_task: Bluetooth chip preload is complete
11-04 00:13:32.583  5956  5979 I bt_btu  : btu_task received preload complete event
,11-04 00:13:32.591  5956  5979 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 00:13:32.591  5956  5979 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-04 00:13:32.591  5956  5979 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 00:13:32.591  5956  5979 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-04 00:13:32.591  5956  5979 I         : BTE_InitTraceLevels -- TRC_AVRC
11-04 00:13:32.591  5956  5979 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 00:13:32.592  5956  5979 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 00:13:32.592  5956  5979 I         : BTE_InitTraceLevels -- TRC_BTM
,11-04 00:13:32.592  5956  5979 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 00:13:32.592  5956  5979 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 00:13:32.592  5956  5979 I         : BTE_InitTraceLevels -- TRC_SDP
,11-04 00:13:32.592  5956  5979 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 00:13:32.592  5956  5979 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 00:13:32.592  5956  5979 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-04 00:13:32.592  5956  5979 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 00:13:32.693  5956  5979 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f79549
,11-04 00:13:32.694  5956  5979 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f79549 
,11-04 00:13:32.716  5956  5972 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 00:13:32.719  5956  5972 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 00:13:32.719  5956  5972 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-04 00:13:32.722  5956  5972 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 00:13:32.724  5956  5972 D BluetoothAdapterProperties: Scan Mode:20
,11-04 00:13:32.724  5956  5972 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 00:13:32.725  5956  5972 D bt_hci  : do_postload posting postload work item
11-04 00:13:32.725  5956  5976 I bt_hci  : event_postload
11-04 00:13:32.725  5956  5976 I bt_vendor: sco_config_cb
11-04 00:13:32.725  5956  5976 I bt_hci  : sco_config_callback postload finished.
11-04 00:13:32.727  5956  5972 D bt_bte_conf: Device ID record 1 : primary
11-04 00:13:32.727  5956  5972 D bt_bte_conf:   vendorId            = 000f
11-04 00:13:32.727  5956  5972 D bt_bte_conf:   vendorIdSource      = 0001
11-04 00:13:32.727  5956  5972 D bt_bte_conf:   product             = 1200
11-04 00:13:32.727  5956  5972 D bt_bte_conf:   version             = 1436
11-04 00:13:32.727  5956  5972 D bt_bte_conf:   clientExecutableURL = 
11-04 00:13:32.727  5956  5972 D bt_bte_conf:   serviceDescription  = 
11-04 00:13:32.727  5956  5972 D bt_bte_conf:   documentationURL    = 
11-04 00:13:32.727  5956  5972 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 00:13:32.728  5956  5969 D bt_stack_manager: event_start_up_stack finished
11-04 00:13:32.729  5956  5968 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 00:13:32.729  5956  5968 D BluetoothAdapterProperties: Setting state to 15
11-04 00:13:32.730  5956  5968 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 00:13:32.731  5956  5968 I BluetoothAdapterState: Entering BleOnState
,11-04 00:13:32.736  5956  5968 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-04 00:13:32.736  5956  5968 D BluetoothAdapterProperties: Setting state to 11
,11-04 00:13:32.737  5956  5968 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-04 00:13:32.737  5956  5976 I bt_vendor: low_power_mode_cb
,11-04 00:13:32.744  5956  5956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
,11-04 00:13:32.745  5956  5956 D HeadsetService: Received start request. Starting profile...
11-04 00:13:32.748  5956  5956 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-04 00:13:32.749  5956  5956 D HeadsetStateMachine: make
,11-04 00:13:32.761  5956  5956 D HeadsetStateMachine: max_hf_connections = 1
,11-04 00:13:32.762  5956  5956 I bt_bluedroid: get_profile_interface handsfree
11-04 00:13:32.762  5956  5972 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 00:13:32.765  5956  5972 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-04 00:13:32.766  5956  5956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
,11-04 00:13:32.766  5956  5956 D A2dpService: Received start request. Starting profile...
11-04 00:13:32.767  5956  5956 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 00:13:32.767  5956  5968 I BluetoothAdapterState: Entering PendingCommandState
11-04 00:13:32.767  5956  5956 I bt_bluedroid: get_profile_interface avrcp
,11-04 00:13:32.774  5956  5956 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 00:13:32.774  5956  5956 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 00:13:32.774  5956  5956 D A2dpStateMachine: make
,11-04 00:13:32.779  5956  5956 I bt_bluedroid: get_profile_interface a2dp
,11-04 00:13:32.781  5956  5972 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-04 00:13:32.783  5956  5986 D A2dpStateMachine: Enter Disconnected: -2
,11-04 00:13:32.783  5956  5956 I BluetoothHidServiceJni: classInitNative: succeeds
,11-04 00:13:32.784  5956  5956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
11-04 00:13:32.785  5956  5956 D HidService: Received start request. Starting profile...
11-04 00:13:32.785  5956  5956 I bt_bluedroid: get_profile_interface hidhost
11-04 00:13:32.785  5956  5972 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f5a56d
11-04 00:13:32.785  5956  5972 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 00:13:32.785  5956  5956 D HidService: setHidService(): set to: null
11-04 00:13:32.786  5956  5956 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 00:13:32.787  5956  5956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
11-04 00:13:32.787  5956  5956 D HealthService: Received start request. Starting profile...
,11-04 00:13:32.789  5956  5956 I bt_bluedroid: get_profile_interface health
,11-04 00:13:32.791  5956  5956 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-04 00:13:32.792  5956  5956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
11-04 00:13:32.792  5956  5956 D PanService: Received start request. Starting profile...
11-04 00:13:32.793  5956  5956 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 00:13:32.793  5956  5956 I bt_bluedroid: get_profile_interface pan
11-04 00:13:32.793  5956  5972 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-04 00:13:32.795  5956  5956 V BluetoothAdapterState: isTurningOff()=false
,11-04 00:13:32.795  5956  5956 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:32.795  5956  5956 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:32.796  5956  5956 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:32.796  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 00:13:32.797  5956  5956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
,11-04 00:13:32.798  5956  5956 D BluetoothMapService: Received start request. Starting profile...
11-04 00:13:32.798  5956  5956 D BluetoothMapService: start()
11-04 00:13:32.801  5956  5956 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-04 00:13:32.802  5956  5956 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 00:13:32.802  5956  5956 D BluetoothMapAppObserver: createReceiver()
11-04 00:13:32.803  5956  5956 D BluetoothMapAppObserver: initObservers()
11-04 00:13:32.803  5956  5956 D BluetoothMapAppObserver: getEnabledAccountItems()
11-04 00:13:32.809  5956  5984 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 00:13:32.809  5956  5956 V SapService: SapBinder()
11-04 00:13:32.809  5956  5956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
11-04 00:13:32.810  5956  5956 D SapService: Received start request. Starting profile...
11-04 00:13:32.810  5956  5956 V SapService: start()
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isTurningOn()=true
,11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:32.812  5956  5956 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:32.813  5956  5956 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:32.813  5956  5956 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:32.813  5956  5956 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:32.813  5956  5956 V BluetoothAdapterState: isBleTurningOff()=false
11-04 00:13:32.814  5956  5956 V BluetoothAdapterState: isTurningOff()=false
11-04 00:13:32.814  5956  5956 V BluetoothAdapterState: isTurningOn()=true
11-04 00:13:32.814  5956  5956 V BluetoothAdapterState: isBleTurningOn()=false
11-04 00:13:32.814  5956  5956 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 00:13:32.815  5956  5968 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 00:13:32.815  5956  5968 D BluetoothAdapterProperties: ScanMode =  20
11-04 00:13:32.815  5956  5968 D BluetoothAdapterProperties: State =  11
11-04 00:13:32.816  5956  5972 D BluetoothAdapterProperties: Scan Mode:21
11-04 00:13:32.817  5956  5968 D BluetoothAdapterProperties: Setting state to 12
11-04 00:13:32.817  5956  5968 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 00:13:32.817  5956  5972 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-04 00:13:32.817  5956  5968 I BluetoothAdapterState: Entering OnState
11-04 00:13:32.818  3123  3139 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 00:13:32.821  5739  5752 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-04 00:13:32.821  3123  3123 D BluetoothMap: Proxy object connected
11-04 00:13:32.821  3123  3123 D MapProfile: Bluetooth service connected
11-04 00:13:32.821  3123  3123 D BluetoothMap: getConnectedDevices()
,11-04 00:13:32.828  5956  5956 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 00:13:32.828  5956  5956 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-04 00:13:32.830  5956  5956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 00:13:32.830   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 00:13:32.831  3123  3140 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 00:13:32.832  5956  5956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 00:13:32.833  3123  3139 D BluetoothPan: onBluetoothStateChange on: true
11-04 00:13:32.833  5956  5956 D ObexServerSockets: Succeed to create listening sockets 
11-04 00:13:32.833  5956  5956 D ObexServerSockets0: startAccept()
11-04 00:13:32.833  5956  5956 D ObexServerSockets0: prepareForNewConnect()
11-04 00:13:32.834  5739  5751 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 00:13:32.835  5956  5956 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 00:13:32.835  5956  5956 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 00:13:32.836  5956  5993 D ObexServerSockets0: Accepting socket connection...
11-04 00:13:32.836  5956  5994 D ObexServerSockets0: Accepting socket connection...
11-04 00:13:32.837  5739  5752 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 00:13:32.838  5739  5739 D BluetoothInputDevice: Proxy object connected
11-04 00:13:32.838  5739  5739 D HidProfile: Bluetooth service connected
11-04 00:13:32.838  3123  3123 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 00:13:32.838  3123  3123 D PanProfile: Bluetooth service connected
11-04 00:13:32.839  3123  3140 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 00:13:32.840  3123  3123 D BluetoothA2dp: Proxy object connected
11-04 00:13:32.840  3796  3825 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 00:13:32.841  5739  5751 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 00:13:32.842  3123  3878 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 00:13:32.843   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 00:13:32.843   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 00:13:32.843   930   930 D BluetoothA2dp: Proxy object connected
11-04 00:13:32.844  5739  5752 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 00:13:32.846   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 00:13:32.847  5739  5995 D BluetoothPan: onBluetoothStateChange on: true
11-04 00:13:32.849  3123  3140 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 00:13:32.851  3123  3123 D BluetoothInputDevice: Proxy object connected
11-04 00:13:32.851  3123  3123 D HidProfile: Bluetooth service connected
11-04 00:13:32.851  5739  5739 D BluetoothA2dp: Proxy object connected
11-04 00:13:32.852   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-04 00:13:32.852  5956  5956 D BluetoothMapService: onReceive
11-04 00:13:32.852  5956  5956 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 00:13:32.852  5956  5956 D BluetoothMapService: STATE_ON
,11-04 00:13:32.854  5739  5739 D BluetoothMap: Proxy object connected
11-04 00:13:32.854  5739  5739 D MapProfile: Bluetooth service connected
,11-04 00:13:32.854  5739  5739 D BluetoothMap: getConnectedDevices()
11-04 00:13:32.854  5956  5996 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 00:13:32.856  5956  5996 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-04 00:13:32.856  5956  5996 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-04 00:13:32.858  5739  5739 D BluetoothPan: BluetoothPAN Proxy object connected
,11-04 00:13:32.858  5739  5739 D PanProfile: Bluetooth service connected
11-04 00:13:32.861  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 00:13:32.867  5739  5739 D DockEventReceiver: finishStartingService: stopping service
,11-04 00:13:32.868  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 00:13:32.875  5739  5739 D BluetoothPbap: Proxy object connected
,11-04 00:13:32.876  5739  5739 D PbapServerProfile: Bluetooth service connected
,11-04 00:13:32.880  5956  5956 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 00:13:32.880  5956  5956 D ObexServerSockets0: prepareForNewConnect()
,11-04 00:13:32.884  5956  6000 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 00:13:32.889  3123  3123 D BluetoothPbap: Proxy object connected
,11-04 00:13:32.890  3123  3123 D PbapServerProfile: Bluetooth service connected
,11-04 00:13:32.901  5956  6004 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 00:13:32.902  5956  6004 I BtOppRfcommListener: Accept thread started.
,11-04 00:13:32.933  3796  4049 D BluetoothHeadset: Proxy object connected
,11-04 00:13:32.933   930   930 D BluetoothHeadset: Proxy object connected
11-04 00:13:32.933   930   930 D BluetoothHeadset: Proxy object connected
11-04 00:13:32.933   930   930 D BluetoothHeadset: Proxy object connected
,11-04 00:13:32.934  5739  5751 D BluetoothHeadset: Proxy object connected
,11-04 00:13:32.934  3123  3139 D BluetoothHeadset: Proxy object connected
11-04 00:13:32.934  3123  3123 D HeadsetProfile: Bluetooth service connected
,11-04 00:13:32.936  5739  5739 D HeadsetProfile: Bluetooth service connected
,11-04 00:13:32.940  5739  5995 D BluetoothHeadset: Proxy object connected
11-04 00:13:32.940  5739  5739 D HeadsetProfile: Bluetooth service connected
,11-04 00:13:32.942  3796  3826 D BluetoothHeadset: Proxy object connected
,11-04 00:13:32.943  3123  3878 D BluetoothHeadset: Proxy object connected
,11-04 00:13:32.943  3123  3123 D HeadsetProfile: Bluetooth service connected
11-04 00:13:32.943   930   947 D BluetoothHeadset: Proxy object connected
,11-04 00:13:32.947   930   947 D BluetoothHeadset: Proxy object connected
,11-04 00:13:33.973   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:34.974   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:35.974   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:36.620  5679  5727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 00:13:36.620  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:36.620  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:36.620  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 00:13:36.620  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 00:13:36.620  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 00:13:36.620  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 00:13:36.620  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 00:13:36.625  5679  5727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 00:13:36.626  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:36.626  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c0b72d removed from the list
11-04 00:13:36.626  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 00:13:36.630  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 00:13:36.631  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7abe462 added. We now have 4 listener(s)
11-04 00:13:36.631  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 00:13:36.634   930  4041 D WifiService: setWifiEnabled: false pid=5679, uid=10077
11-04 00:13:36.634   930  4041 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 00:13:36.975   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:37.976   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:38.977   602   602 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-04 00:13:39.571   930   950 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-04 00:13:39.577  3819  3819 W Binder_8: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32387]" dev="sockfs" ino=32387 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 00:13:39.577  3819  3819 W Binder_8: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32387]" dev="sockfs" ino=32387 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 00:13:39.589  3675  3675 I Keyboard.Facilitator: onFinishInput()
,11-04 00:13:39.603   930   950 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 00:13:39.603   930   950 I Adreno  : Build Date                       : 12/06/15
11-04 00:13:39.603   930   950 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 00:13:39.603   930   950 I Adreno  : Local Branch                     : mybranch17112971
11-04 00:13:39.603   930   950 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 00:13:39.603   930   950 I Adreno  : Remote Branch                    : NONE
11-04 00:13:39.603   930   950 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 00:13:39.639   381   953 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (136 us)
,11-04 00:13:40.300  5679  5679 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-04 00:13:40.300  5679  5679 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-04 00:13:40.332   930   950 I sensors : batch
,11-04 00:13:40.333   930   950 V KeyguardServiceDelegate: onScreenTurnedOff()
11-04 00:13:40.334  5679  5679 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2718357 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@99249f3, 16908290=android.view.AbsSavedState$1@99249f3}, android:focusedViewId=100}]}]
11-04 00:13:40.334  5679  5679 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,11-04 00:13:40.335  5679  5679 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 00:13:40.335  5679  5679 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,11-04 00:13:40.340   930   950 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-04 00:13:40.340   930   950 I sensors : activate
,11-04 00:13:40.341   381   381 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fb29c3c00
,11-04 00:13:40.342   930   948 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-04 00:13:40.342   381   381 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-04 00:13:40.344   930  2753 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-04 00:13:40.346   930  2753 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-04 00:13:40.647   381   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-04 00:13:40.651   381   381 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-04 00:13:40.652   930  3078 D SurfaceControl: Excessive delay in setPowerMode(): 310ms
,11-04 00:13:40.667   930   950 I DreamManagerService: Entering dreamland.
,11-04 00:13:40.668   930   950 I PowerManagerService: Dozing...
,11-04 00:13:40.669   930   945 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-04 00:13:40.697  3819  3819 W Binder_8: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[34899]" dev="sockfs" ino=34899 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 00:13:40.697  3819  3819 W Binder_8: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[34899]" dev="sockfs" ino=34899 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 00:13:40.702   930  3450 I sensors : batch
11-04 00:13:40.702   930  3450 I sensors : activate
,11-04 00:13:40.706   930  2753 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-04 00:13:40.707   930  2753 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-04 00:13:40.712   514  3029 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-04 00:13:40.745  3796  4716 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-04 00:13:40.745  3796  4716 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 00:13:40.745  3796  4716 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 00:13:40.746   527  1352 D         : oem-qmi: Connection accepted
11-04 00:13:40.746   527  1352 D         : oem-qmi: Waiting to accept connection
,11-04 00:13:40.748   930   930 I sensors : activate
,11-04 00:13:40.749   514  3696 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-04 00:13:40.752   930  2753 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-04 00:13:40.753  3796  4716 D         : oem_qmi_lib:output 0
,11-04 00:13:40.753  3796  4716 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 00:13:40.787  3796  4716 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-04 00:13:40.787  3796  4716 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 00:13:40.787  3796  4716 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 00:13:40.787   527  1352 D         : oem-qmi: Connection accepted
,11-04 00:13:40.787   527  1352 D         : oem-qmi: Waiting to accept connection
,11-04 00:13:40.794  3796  4716 D         : oem_qmi_lib:output 0
,11-04 00:13:40.795  3796  4716 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 00:13:41.647  5679  5727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 00:13:41.648   930  3819 D WifiService: setWifiEnabled: true pid=5679, uid=10077
,11-04 00:13:41.648   930  3819 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 00:13:41.655   509   923 D SoftapController: Softap fwReload - Ok
,11-04 00:13:41.660   509   923 D CommandListener: Setting iface cfg
,11-04 00:13:41.661   509   923 D CommandListener: Trying to bring down wlan0
,11-04 00:13:41.663   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-04 00:13:41.670   930  3019 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 00:13:42.278   930  3019 D wifi    : set interface wlan0 flags (UP)
,11-04 00:13:42.283   930  3019 I WifiHAL : Initializing wifi
11-04 00:13:42.283   930  3019 I WifiHAL : Creating socket
,11-04 00:13:42.288   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 00:13:42.289   930  3019 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-04 00:13:42.290   930  3019 D wifi    : Did set static halHandle = 0x7f74fd1b80
11-04 00:13:42.290   930  3019 D wifi    : halHandle = 0x7f74fd1b80, mVM = 0x7f9160d140, mCls = 0x18e2
11-04 00:13:42.290   930  3019 D wifi    : array field set
,11-04 00:13:42.290   930  3019 I WifiNative-HAL: interface[0] = wlan0
11-04 00:13:42.292   930  6017 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547423591296
11-04 00:13:42.293   930  6017 D wifi    : waitForHalEvents called, vm = 0x7f9160d140, obj = 0x18e2, env = 0x7f795da1c0
,11-04 00:13:42.352  6018  6018 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 00:13:42.393   930  3019 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 00:13:42.422  6018  6018 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 00:13:42.467  6018  6018 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 00:13:42.467  6018  6018 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 00:13:42.481   930  3019 D WifiConfigStore: Loading config and enabling all networks 
,11-04 00:13:42.508   930  3019 D WifiConfigStore: loaded 0 passpoint configs
,11-04 00:13:42.509   930  3019 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-04 00:13:42.509   930  3019 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-04 00:13:42.510   930  3019 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-04 00:13:42.511   930  3019 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-04 00:13:42.512   930  3019 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-04 00:13:42.512   930  3019 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-04 00:13:42.513   930  3019 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 00:13:42.513   930  3019 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 00:13:42.513   930  3019 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-04 00:13:42.513   930  3019 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-04 00:13:42.513   930  3019 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 00:13:42.513   930  3019 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 00:13:42.515   930  3019 D WifiNative-HAL: Setting external_sim to 1
,11-04 00:13:42.516   930  3019 D wifi    : setting dfs flag to true, 0x7f7a2bfaa0
11-04 00:13:42.516   930  3019 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 00:13:42.516   930  3019 D wifi    : setting scan oui 0x7f7a2bfaa0
11-04 00:13:42.516   930  3019 D WifiHAL : Sending mac address OUI
11-04 00:13:42.516  4546  4546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 00:13:42.519   930  3019 E native  : do suspend true
,11-04 00:13:42.525   930  3019 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-04 00:13:42.525   930   930 D RttService: SCAN_AVAILABLE : 3
11-04 00:13:42.525   930  3072 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 00:13:42.532   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-04 00:13:42.533   509   923 D CommandListener: Setting iface cfg
,11-04 00:13:42.537   930  3007 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
11-04 00:13:42.537   930  3007 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 00:13:42.545   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=151463 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
,11-04 00:13:42.546   930  3007 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 00:13:42.546   930  3007 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 00:13:45.605  3724  4458 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-04 00:13:45.695  6018  6018 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 00:13:45.727   930  3019 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 00:13:45.730   930  3019 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,11-04 00:13:45.731   930  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 00:13:45.749   930  3019 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 00:13:45.799   930  3019 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 00:13:46.137  6018  6018 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 00:13:46.171  6018  6018 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 00:13:46.173  6018  6018 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 00:13:46.184   930  3019 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-04 00:13:46.184   930  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 00:13:46.184   930  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 00:13:46.201   930  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 00:13:46.213   509   923 D CommandListener: Setting iface cfg
,11-04 00:13:46.220   930  3019 D WifiStateMachine: Start Dhcp Watchdog 3
,11-04 00:13:46.224   930  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-04 00:13:46.229   930  6032 D DhcpClient: Receive thread started
,11-04 00:13:46.312   930  3019 E native  : do suspend false
,11-04 00:13:46.323   930  6031 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 00:13:46.347   930  6032 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-04 00:13:46.348   930  6031 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-04 00:13:46.350   930  6031 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 00:13:46.363   930  6032 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-04 00:13:46.364   930  6031 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 00:13:46.369   509   923 D CommandListener: Setting iface cfg
11-04 00:13:46.374   930  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 00:13:46.381   930  3019 E native  : do suspend true
,11-04 00:13:46.381   930  6031 D DhcpClient: Scheduling renewal in 86399s
,11-04 00:13:46.399   930  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-04 00:13:46.401   930  3019 D WifiConfigStore: No blacklist allowed without epno enabled
,11-04 00:13:46.402   930  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-04 00:13:46.404   930  3021 D ConnectivityService: Adding iface wlan0 to network 102
11-04 00:13:46.410   930  3019 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 00:13:46.455   930  3021 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-04 00:13:46.455   930  3021 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-04 00:13:46.457   930  3021 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-04 00:13:46.459   930  3021 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-04 00:13:46.461   930  3021 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-04 00:13:46.468   930  3021 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-04 00:13:46.472   930  3021 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-04 00:13:46.472   930  3021 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-04 00:13:46.472   930  3021 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-04 00:13:46.472   930  3021 D ConnectivityService:    accepting network in place of null
11-04 00:13:46.472   930  3019 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 00:13:46.473   930  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 00:13:46.473   930  3021 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 00:13:46.486   930  6030 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155404, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 00:13:46.497   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 00:13:46.521   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 00:13:46.527   930  3021 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-04 00:13:46.527   930  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 00:13:46.527  3758  3888 W QCNEJ   : |CORE| network available: 102
,11-04 00:13:46.529   930  3021 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-04 00:13:46.529  3758  3888 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-04 00:13:46.530  3758  3888 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-04 00:13:46.530  3758  3888 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-04 00:13:46.531   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-04 00:13:46.542  3978  3978 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-04 00:13:46.545  4015  4015 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-04 00:13:46.549  4015  4015 D SystemUpdateService: onCreate
,11-04 00:13:46.554  4015  4015 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 00:13:46.564  4015  4015 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 00:13:46.565   930  6029 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
11-04 00:13:46.569  4015  4241 I iu.UploadsManager: num queued entries: 0
11-04 00:13:46.569  4015  4241 I iu.UploadsManager: num updated entries: 0
11-04 00:13:46.570  4015  4241 I iu.SyncManager: NEXT; no task
,11-04 00:13:46.574  4015  6041 I SystemUpdateService: active receiver: enabled
,11-04 00:13:46.576  4015  4015 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 00:13:46.577  4015  4015 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 00:13:46.579  5799  5799 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 00:13:46.583  5799  5799 D SprintDMHelper: simOperator: 
11-04 00:13:46.583  5799  5799 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 00:13:46.607  4015  6041 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 00:13:46.610   930  6029 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 23:13:46 GMT], X-Android-Received-Millis=[1478214826610], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478214826589]}
,11-04 00:13:46.611   930  3021 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 00:13:46.611   930  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-04 00:13:46.611   930  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-04 00:13:46.612   930  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 00:13:46.614  4015  6041 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 00:13:46.614  4015  6041 I SystemUpdateService: now status is 0 (complete)
11-04 00:13:46.614  4015  6041 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 00:13:46.614  4015  6041 I SystemUpdateService: file has been verified
11-04 00:13:46.615  4015  6041 I SystemUpdateService: OTA package size = 21989297
,11-04 00:13:46.622  4015  6041 I SystemUpdateService: showing system update notification
,11-04 00:13:46.631   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 00:13:46.632  4015  4015 D SystemUpdateService: onDestroy
,11-04 00:13:46.659  5679  5727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 00:13:46.659  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 00:13:46.659  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 00:13:46.659  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 00:13:46.659  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 00:13:46.659  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 00:13:46.659  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 00:13:46.659  5679  5727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 00:13:46.661  5679  5727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 00:13:46.661  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.661  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7abe462 removed from the list
11-04 00:13:46.661  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 00:13:46.664  5679  5727 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-04 00:13:46.664  5679  5727 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-04 00:13:46.666  5679  5727 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2718357 Bundle[{}]
,11-04 00:13:46.666  5679  5727 I io.jxcore.node.LifeCycleMonitor: start: OK
11-04 00:13:46.666  5679  5727 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-04 00:13:46.667  5679  5727 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-04 00:13:46.667  5679  5727 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 00:13:46.667  5679  5727 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-04 00:13:46.667  5679  5727 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-04 00:13:46.672  5679  5727 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-04 00:13:46.672  5679  5727 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-04 00:13:46.672  5679  5727 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
11-04 00:13:46.673  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 00:13:46.673  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac3b6b0 added. We now have 3 listener(s)
11-04 00:13:46.675  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 00:13:46.675  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 00:13:46.675  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 00:13:46.675  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:13:46.675  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31e9929 added. We now have 4 listener(s)
11-04 00:13:46.675  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 00:13:46.675  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 00:13:46.677  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 00:13:46.677  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@567e4ae added. We now have 4 listener(s)
,11-04 00:13:46.678  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 00:13:46.678  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 00:13:46.678  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 00:13:46.678  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:13:46.678  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d924f added. We now have 5 listener(s)
11-04 00:13:46.679  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 00:13:46.679  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:13:46.679  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:13:46.679  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:13:46.679  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:13:46.679  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:13:46.679  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 00:13:46.679  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac3b6b0 removed from the list
,11-04 00:13:46.679  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.679  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31e9929 removed from the list
11-04 00:13:46.679  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:13:46.679  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.681  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.681  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.681  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.681  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 00:13:46.681  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:13:46.681  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.681  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31e9929 not in the list
11-04 00:13:46.681  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.683  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.683  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.683  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.683  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:13:46.683  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:13:46.683  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.683  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d924f removed from the list
,11-04 00:13:46.683  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:13:46.684  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:13:46.684  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 00:13:46.684  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@567e4ae removed from the list
,11-04 00:13:46.684  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 00:13:46.685  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d258ddc added. We now have 3 listener(s)
,11-04 00:13:46.686  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 00:13:46.686  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 00:13:46.687  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 00:13:46.687  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:13:46.687  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5e9ee5 added. We now have 4 listener(s)
11-04 00:13:46.687  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 00:13:46.687  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 00:13:46.689  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 00:13:46.689  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd19dba added. We now have 4 listener(s)
,11-04 00:13:46.690  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 00:13:46.690  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 00:13:46.690  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 00:13:46.691  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:13:46.691  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b046b added. We now have 5 listener(s)
11-04 00:13:46.691  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 00:13:46.691  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 00:13:46.691  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 00:13:46.691  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 00:13:46.691  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 00:13:46.691  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 00:13:46.693  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 00:13:46.696  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-04 00:13:46.696  5679  5727 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 00:13:46.696  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 00:13:46.699  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.699  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 00:13:46.700  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 00:13:46.700  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 00:13:46.700  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 00:13:46.703  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.703  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 00:13:46.703  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 00:13:46.703  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 00:13:46.703  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 00:13:46.703  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.704  5679  5727 D BluetoothAdapter: STATE_ON
,11-04 00:13:46.706  5956  5992 D BtGatt.GattService: registerClient() - UUID=154f2f4f-c2df-4c1f-bb70-faf98e485813
,11-04 00:13:46.707  5956  5972 D BtGatt.GattService: onClientRegistered() - UUID=154f2f4f-c2df-4c1f-bb70-faf98e485813, clientIf=5
,11-04 00:13:46.707  5679  5689 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 00:13:46.708  5956  5991 D BtGatt.GattService: start scan with filters
11-04 00:13:46.710  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 00:13:46.711  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.711  5956  5975 D BtGatt.ScanManager: handling starting scan
11-04 00:13:46.711  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 00:13:46.711  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.711  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 00:13:46.711  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 00:13:46.711  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.711  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 00:13:46.711  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 00:13:46.711  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.711  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.711  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-04 00:13:46.712  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 00:13:46.712  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.713  5956  5975 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7521098
,11-04 00:13:46.714  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.714  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 00:13:46.714  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.714  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.714  5679  5727 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 00:13:46.714  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 00:13:46.715  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 00:13:46.714  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.715  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 00:13:46.715  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 00:13:46.715  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:13:46.715  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-04 00:13:46.717  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.718  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.718  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.718  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.718  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 00:13:46.718  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 00:13:46.718  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 00:13:46.718  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 00:13:46.718  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.718  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.718  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.718  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 00:13:46.718  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.719  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:13:46.719  5956  5991 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-04 00:13:46.719  5956  5972 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 00:13:46.719  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.719  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 00:13:46.720  5956  5975 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 00:13:46.720  5679  5727 D BluetoothAdapter: STATE_ON
,11-04 00:13:46.720  5956  5966 D BtGatt.GattService: stopScan() - queue size =1
,11-04 00:13:46.721  5956  5992 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 00:13:46.721  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 00:13:46.721  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.721  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 00:13:46.721  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.721  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.722  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.722  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.722  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 00:13:46.722  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.722  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.722  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.722  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 00:13:46.722  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 00:13:46.722  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 00:13:46.723  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.723  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.724  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 00:13:46.724  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.724  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.724  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:13:46.724  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:13:46.724  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 00:13:46.724  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.724  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 00:13:46.724  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 00:13:46.724  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.725  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.725  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 00:13:46.725  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.725  5956  5972 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 00:13:46.725  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 00:13:46.725  5956  5975 D BtGatt.ScanManager: Starting BLE batch scan
11-04 00:13:46.725  5956  5975 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 00:13:46.726  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.726  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.726  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.726  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.726  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 00:13:46.727  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:13:46.727  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:13:46.727  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:13:46.727  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:13:46.727  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:13:46.727  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 00:13:46.727  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d258ddc removed from the list
11-04 00:13:46.727  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 00:13:46.727  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5e9ee5 removed from the list
11-04 00:13:46.727  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:13:46.728  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.728  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.729  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.729  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.729  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 00:13:46.729  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:13:46.729  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.729  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5e9ee5 not in the list
11-04 00:13:46.729  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.730  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.730  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.730  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.730  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:13:46.730  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:13:46.730  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.730  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b046b removed from the list
11-04 00:13:46.730  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:13:46.731  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:13:46.731  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-04 00:13:46.731  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd19dba removed from the list
11-04 00:13:46.731  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 00:13:46.731  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73bc74 added. We now have 3 listener(s)
11-04 00:13:46.732  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 00:13:46.733  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 00:13:46.733  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 00:13:46.733  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:13:46.733  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ac59d added. We now have 4 listener(s)
,11-04 00:13:46.733  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 00:13:46.734  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 00:13:46.735  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 00:13:46.735  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a2a12 added. We now have 4 listener(s)
,11-04 00:13:46.736  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 00:13:46.736  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 00:13:46.736  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 00:13:46.736  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:13:46.736  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be195e3 added. We now have 5 listener(s)
11-04 00:13:46.736  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 00:13:46.736  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 00:13:46.736  5956  5972 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 00:13:46.736  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.737  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 00:13:46.737  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-04 00:13:46.737  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 00:13:46.737  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 00:13:46.737  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 00:13:46.741  5956  5972 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 00:13:46.741  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.741  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 00:13:46.743  5956  5975 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 00:13:46.743  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 00:13:46.744  5679  5727 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 00:13:46.744  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 00:13:46.747  5956  5972 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 00:13:46.747  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.748  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.748  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 00:13:46.748  5956  5972 E BtGatt.ContextMap: Context not found for ID 5
11-04 00:13:46.748  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-04 00:13:46.748  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 00:13:46.748  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 00:13:46.751  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.751  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 00:13:46.751  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 00:13:46.751  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 00:13:46.751  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 00:13:46.751  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.752  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:13:46.753  5956  5992 D BtGatt.GattService: registerClient() - UUID=7b09919b-0c7f-44c3-a7fd-39ed9f1b0cef
11-04 00:13:46.754  5956  5972 D BtGatt.GattService: onClientRegistered() - UUID=7b09919b-0c7f-44c3-a7fd-39ed9f1b0cef, clientIf=5
,11-04 00:13:46.755  5956  5972 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 00:13:46.755  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.755  5679  5690 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 00:13:46.755  5956  5975 D BtGatt.ScanManager: stopping BLe Batch
11-04 00:13:46.755  5956  5967 D BtGatt.GattService: start scan with filters
11-04 00:13:46.760  5956  5972 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 00:13:46.760  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.760  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 00:13:46.760  5956  5975 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 00:13:46.760  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.760  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 00:13:46.760  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.760  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 00:13:46.761  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 00:13:46.761  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-04 00:13:46.761  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 00:13:46.761  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 00:13:46.761  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.761  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.761  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-04 00:13:46.762  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 00:13:46.762  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 00:13:46.764  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.764  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 00:13:46.764  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.764  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.764  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.764  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 00:13:46.764  5679  5727 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-04 00:13:46.764  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:13:46.764  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:13:46.764  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 00:13:46.764  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:13:46.764  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 00:13:46.764  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 00:13:46.764  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:13:46.764  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 00:13:46.764  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73bc74 removed from the list
11-04 00:13:46.764  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.764  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ac59d removed from the list
11-04 00:13:46.765  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:13:46.765  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 00:13:46.765  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 00:13:46.765  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-04 00:13:46.765  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-04 00:13:46.765  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 00:13:46.765  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 00:13:46.765  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.765  5956  5972 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 00:13:46.765  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.766  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.766  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-04 00:13:46.766  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.766  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.766  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.766  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 00:13:46.766  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.767  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.767  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 00:13:46.767  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:13:46.767  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.767  5956  5975 D BtGatt.ScanManager: handling starting scan
11-04 00:13:46.767  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ac59d not in the list
11-04 00:13:46.767  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 00:13:46.767  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 00:13:46.767  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 00:13:46.767  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.767  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.767  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.767  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 00:13:46.767  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.768  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:13:46.768  5956  5992 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 00:13:46.768  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 00:13:46.769  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:13:46.769  5956  5991 D BtGatt.GattService: stopScan() - queue size =1
11-04 00:13:46.770  5956  5966 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 00:13:46.770  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 00:13:46.770  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.770  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 00:13:46.770  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.770  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.770  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.770  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.771  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 00:13:46.771  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.771  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.771  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.771  5679  5727 D org.thaliproject.p2p.,btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 00:13:46.771  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 00:13:46.772  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 00:13:46.772  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.773  5956  5972 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 00:13:46.773  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.773  5956  5975 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 00:13:46.773  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.773  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 00:13:46.773  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.773  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.773  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:13:46.773  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:13:46.773  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.773  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be195e3 removed from the list
11-04 00:13:46.773  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:13:46.773  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:13:46.773  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 00:13:46.774  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a2a12 removed from the list
11-04 00:13:46.774  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 00:13:46.774  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@956260c added. We now have 3 listener(s)
11-04 00:13:46.775  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:13:46.775  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:13:46.775  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 00:13:46.775  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.775  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 00:13:46.775  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 00:13:46.775  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothCo,nnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 00:13:46.775  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 00:13:46.775  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 00:13:46.775  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.775  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.775  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:13:46.776  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 00:13:46.776  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28e0b55 added. We now have 4 listener(s)
11-04 00:13:46.776  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.776  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 00:13:46.776  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 00:13:46.777  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.777  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.777  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.777  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.778  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 00:13:46.778  5956  5972 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 00:13:46.778  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.778  5956  5975 D BtGatt.ScanManager: Starting BLE batch scan
11-04 00:13:46.778  5956  5975 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 00:13:46.778  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 00:13:46.779  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ace96a added. We now have 4 listener(s)
11-04 00:13:46.780  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 00:13:46.780  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 00:13:46.780  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 00:13:46.780  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:13:46.780  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b9de5b added. We now have 5 listener(s)
11-04 00:13:46.780  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 00:13:46.781  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 00:13:46.781  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 00:13:46.781  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 00:13:46.781  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 00:13:46.781  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 00:13:46.782  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 00:13:46.784  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 00:13:46.784  5679  5727 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 00:13:46.784  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 00:13:46.787  5956  5972 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 00:13:46.787  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.788  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.789  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 00:13:46.789  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 00:13:46.789  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 00:13:46.789  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-04 00:13:46.792  5956  5972 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 00:13:46.792  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.793  5956  5975 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 00:13:46.793  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.794  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 00:13:46.794  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 00:13:46.794  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 00:13:46.794  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 00:13:46.794  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.795  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:13:46.796  5956  5991 D BtGatt.GattService: registerClient() - UUID=648f7052-4f26-44df-976e-c3ec35fc3f17
11-04 00:13:46.797  5956  5972 D BtGatt.GattService: onClientRegistered() - UUID=648f7052-4f26-44df-976e-c3ec35fc3f17, clientIf=5
11-04 00:13:46.797  5679  5690 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 00:13:46.797  5956  5992 D BtGatt.GattService: start scan with filters
11-04 00:13:46.798  5956  5972 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 00:13:46.798  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.800  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 00:13:46.801  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.801  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 00:13:46.801  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.801  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 00:13:46.801  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.801  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 00:13:46.801  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.801  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 00:13:46.801  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 00:13:46.801  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.801  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.801  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 00:13:46.802  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 00:13:46.802  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.804  5956  5972 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 00:13:46.804  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.804  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.804  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 00:13:46.804  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.804  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.804  5956  5975 D BtGatt.ScanManager: stopping BLe Batch
11-04 00:13:46.804  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.807  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:13:46.807  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:13:46.807  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:13:46.807  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:13:46.807  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 00:13:46.807  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 00:13:46.807  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:13:46.807  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 00:13:46.807  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@956260c removed from the list
11-04 00:13:46.807  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.807  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28e0b55 removed from the list
11-04 00:13:46.807  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:13:46.807  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 00:13:46.807  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 00:13:46.807  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-04 00:13:46.807  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-04 00:13:46.807  5679  5727 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 00:13:46.807  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 00:13:46.807  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.808  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.808  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.808  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.808  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.808  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 00:13:46.811  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.811  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.811  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.811  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:13:46.811  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:13:46.811  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.811  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28e0b55 not in the list
11-04 00:13:46.811  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 00:13:46.811  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 00:13:46.811  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 00:13:46.811  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.811  5956  5972 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 00:13:46.811  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.811  5956  5975 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 00:13:46.811  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.815  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.815  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 00:13:46.815  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.816  5956  5972 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 00:13:46.816  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.816  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:13:46.816  5956  5966 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 00:13:46.816  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 00:13:46.817  5679  5727 D BluetoothAdapter: STATE_ON
11-04 00:13:46.817  5956  5975 D BtGatt.ScanManager: handling starting scan
11-04 00:13:46.817  5956  5967 D BtGatt.GattService: stopScan() - queue size =0
11-04 00:13:46.818  5956  5966 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 00:13:46.818  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 00:13:46.818  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.818  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 00:13:46.818  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.818  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.819  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.819  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.819  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 00:13:46.819  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.819  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.819  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.819  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 00:13:46.819  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 00:13:46.819  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 00:13:46.820  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.821  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.821  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 00:13:46.821  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.821  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.821  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:13:46.821  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:13:46.821  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.821  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:13:46.821  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b9de5b removed from the list
11-04 00:13:46.821  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:13:46.822  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 00:13:46.822  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:13:46.822  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 00:13:46.822  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ace96a removed from the list
11-04 00:13:46.822  5679  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 00:13:46.822  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.822  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 00:13:46.822  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 00:13:46.822  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.822  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.822  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 00:13:46.822  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.822  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 00:13:46.822  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b92aa4 added. We now have 3 listener(s)
11-04 00:13:46.823  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.823  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.823  5679  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.823  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 00:13:46.823  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 00:13:46.823  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 00:13:46.823  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 00:13:46.823  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 00:13:46.824  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:13:46.824  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad500d added. We now have 4 listener(s)
11-04 00:13:46.824  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 00:13:46.824  5956  5972 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 00:13:46.824  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.824  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 00:13:46.824  5956  5975 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 00:13:46.826  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 00:13:46.826  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3d3bc2 added. We now have 4 listener(s)
11-04 00:13:46.828  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 00:13:46.828  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 00:13:46.828  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 00:13:46.828  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 00:13:46.828  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f53bdd3 added. We now have 5 listener(s)
11-04 00:13:46.828  5679  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 00:13:46.829  5679  5727 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 00:13:46.829  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:13:46.829  5679  5727 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 00:13:46.829  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:13:46.829  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:13:46.829  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 00:13:46.829  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b92aa4 removed from the list
11-04 00:13:46.829  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.829  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad500d removed from the list
11-04 00:13:46.830  5679  5727 D io.jxcore.node.ConnectivityMonitor: stop
11-04 00:13:46.830  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.830  5956  5972 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 00:13:46.830  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.830  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.830  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.831  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.831  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:13:46.831  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:13:46.831  5956  5975 D BtGatt.ScanManager: Starting BLE batch scan
11-04 00:13:46.831  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.831  5956  5975 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 00:13:46.831  5679  5727 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad500d not in the list
11-04 00:13:46.831  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.832  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.832  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.832  5679  5727 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 00:13:46.832  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 00:13:46.832  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 00:13:46.832  5679  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 00:13:46.832  5679  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f53bdd3 removed from the list
11-04 00:13:46.832  5679  5727 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 00:13:46.832  5679  5727 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 00:13:46.832  5679  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 00:13:46.832  5679  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3d3bc2 removed from the list
11-04 00:13:46.834  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-04 00:13:46.834  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 00:13:46.834  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 00:13:46.834  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 00:13:46.834  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-04 00:13:46.834  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 00:13:46.839  5956  5972 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 00:13:46.839  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.843  5956  5972 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 00:13:46.843  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.845  5956  5975 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 00:13:46.849  5956  5972 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 00:13:46.849  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.849  5956  5972 E BtGatt.ContextMap: Context not found for ID 5
,11-04 00:13:46.854  5956  5972 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 00:13:46.854  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.854  5956  5975 D BtGatt.ScanManager: stopping BLe Batch
11-04 00:13:46.858  5956  5972 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 00:13:46.858  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 00:13:46.858  5956  5975 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 00:13:46.862  5956  5972 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 00:13:46.862  5956  5972 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 00:13:47.228  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 00:13:47.278  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 00:13:47.324  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 00:13:47.922   930  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,11-04 00:13:47.936   930  3021 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-04 00:13:47.943  3758  3888 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-04 00:13:47.943  3758  3888 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-04 00:13:48.974  5679  6049 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 00:13:48.974  5679  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 00:13:49.777  5679  6049 W !!      : call onHalfStreamCopied
,11-04 00:13:49.777  5679  6049 I testCopyDataAndClose: closing input stream
,11-04 00:13:49.957  3620  6051 I VacuumService: Vacuum at: now=1478214829957 tag=VacuumService
,11-04 00:13:50.002  3620  6054 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-04 00:13:50.033  3620  6052 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-04 00:13:50.037  3620  6052 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-04 00:13:50.056  3620  6052 W Uploader:  no longer exists, so no auth token.
,11-04 00:13:50.062  3620  6054 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 00:13:50.290  3620  6056 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 00:13:50.408  3620  6054 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 00:13:50.470  3620  6052 W Uploader:  no longer exists, so no auth token.
,11-04 00:13:50.475  3620  6056 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 00:13:50.537  5679  6049 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 00:13:50.537  5679  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 00:13:50.537  5679  6049 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 00:13:50.537  5679  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 00:13:50.537  5679  6049 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 00:13:50.537  5679  6049 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-04 00:13:50.537  5679  6049 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 00:13:50.537  5679  6049 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 00:13:50.537  5679  6049 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 00:13:50.537  5679  6049 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 00:13:50.537  5679  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 00:13:50.559  3620  6054 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 00:13:50.630  3620  6056 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 00:13:53.978   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:54.479   930  3021 D ConnectivityService: handlePromptUnvalidated 102
,11-04 00:13:54.980   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:55.002  5679  6061 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-04 00:13:55.002  5679  6061 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 00:13:55.982   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:56.983   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:57.001  5679  5727 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-04 00:13:57.001  5679  5727 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 00:13:57.002  5679  5727 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-04 00:13:57.186  5679  6062 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 00:13:57.186  5679  6062 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 00:13:57.237  5679  6061 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-04 00:13:57.237  5679  6061 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-04 00:13:57.237  5679  6061 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-04 00:13:57.984   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:13:58.806  5679  6062 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 00:13:58.806  5679  6062 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 00:13:58.806  5679  6062 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 00:13:58.806  5679  6062 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 00:13:58.806  5679  6062 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-04 00:13:58.806  5679  6062 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-04 00:13:58.806  5679  6062 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 00:13:58.806  5679  6062 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-04 00:13:58.806  5679  6062 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 00:13:58.806  5679  6062 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 00:13:58.806  5679  6062 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 00:13:58.985   602   602 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-04 00:14:03.263  5679  6063 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-04 00:14:03.263  5679  6063 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 00:14:03.263  5679  6063 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-04 00:14:03.263  5679  6063 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 00:14:03.263  5679  6063 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 00:14:03.263  5679  6063 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 00:14:03.263  5679  6063 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 00:14:03.264  5679  6063 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-04 00:14:03.264  5679  6063 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 00:14:03.264  5679  6063 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 00:14:03.264  5679  6063 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 00:14:03.264  5679  6063 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-04 00:14:03.264  5679  6063 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-04 00:14:03.277  5679  5727 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-04 00:14:03.280  5679  6064 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 00:14:03.280  5679  6064 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 00:14:03.280  5679  6064 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-04 00:14:03.280  5679  6064 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 00:14:03.280  5679  6064 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-04 00:14:03.281  5679  6064 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-04 00:14:03.281  5679  6064 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 00:14:03.281  5679  6064 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-04 00:14:03.287  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-04 00:14:03.287  5679  5727 I jxcore-log: 
,11-04 00:14:03.287  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-04 00:14:03.287  5679  5727 I jxcore-log: 
11-04 00:14:03.287  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-04 00:14:03.287  5679  5727 I jxcore-log: 
11-04 00:14:03.288  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-04 00:14:03.288  5679  5727 I jxcore-log: 
,11-04 00:14:03.288  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG UnitTest_app: 'Total duration:  92229'
11-04 00:14:03.288  5679  5727 I jxcore-log: 
,11-04 00:14:03.290  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-04 00:14:03.290  5679  5727 I jxcore-log: 
,11-04 00:14:03.295  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 00:14:03.295  5679  5727 I jxcore-log: 
,11-04 00:14:03.305  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 00:14:03.305  5679  5727 I jxcore-log: 
,11-04 00:14:03.305  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 00:14:03.305  5679  5727 I jxcore-log: 
11-04 00:14:03.306  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-04 00:14:03.306  5679  5727 I jxcore-log: 
,11-04 00:14:03.312  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 00:14:03.312  5679  5727 I jxcore-log: 
,11-04 00:14:03.313  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 00:14:03.313  5679  5727 I jxcore-log: 
11-04 00:14:03.313  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 00:14:03.313  5679  5727 I jxcore-log: 
,11-04 00:14:03.318  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 00:14:03.318  5679  5727 I jxcore-log: 
,11-04 00:14:03.318  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 00:14:03.318  5679  5727 I jxcore-log: 
11-04 00:14:03.318  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 00:14:03.318  5679  5727 I jxcore-log: 
11-04 00:14:03.319  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-04 00:14:03.319  5679  5727 I jxcore-log: 
11-04 00:14:03.319  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 00:14:03.319  5679  5727 I jxcore-log: 
,11-04 00:14:03.319  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 00:14:03.319  5679  5727 I jxcore-log: 
11-04 00:14:03.319  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 00:14:03.319  5679  5727 I jxcore-log: 
11-04 00:14:03.319  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 00:14:03.319  5679  5727 I jxcore-log: 
,11-04 00:14:03.320  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 00:14:03.320  5679  5727 I jxcore-log: 
11-04 00:14:03.320  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 00:14:03.320  5679  5727 I jxcore-log: 
11-04 00:14:03.320  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 00:14:03.320  5679  5727 I jxcore-log: 
11-04 00:14:03.320  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 00:14:03.320  5679  5727 I jxcore-log: 
11-04 00:14:03.321  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 00:14:03.321  5679  5727 I jxcore-log: 
11-04 00:14:03.321  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 00:14:03.321  5679  5727 I jxcore-log: 
,11-04 00:14:03.321  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 00:14:03.321  5679  5727 I jxcore-log: 
11-04 00:14:03.322  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 00:14:03.322  5679  5727 I jxcore-log: 
,11-04 00:14:03.322  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 00:14:03.322  5679  5727 I jxcore-log: 
,11-04 00:14:03.323  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 00:14:03.323  5679  5727 I jxcore-log: 
11-04 00:14:03.323  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 00:14:03.323  5679  5727 I jxcore-log: 
11-04 00:14:03.324  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 00:14:03.324  5679  5727 I jxcore-log: 
11-04 00:14:03.324  5679  5679 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-04 00:14:03.324  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 00:14:03.324  5679  5727 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-04 00:14:03.324  5679  5727 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 00:14:03.324  5679  5727 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-04 00:14:03.324  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 00:14:03.324  5679  5727 I jxcore-log: 
11-04 00:14:03.325  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 00:14:03.325  5679  5727 I jxcore-log: 
11-04 00:14:03.325  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 00:14:03.325  5679  5727 I jxcore-log: 
11-04 00:14:03.325  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 00:14:03.325  5679  5727 I jxcore-log: 
11-04 00:14:03.325  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 00:14:03.325  5679  5727 I jxcore-log: 
11-04 00:14:03.325  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 00:14:03.325  5679  5727 I jxcore-log: 
,11-04 00:14:03.331  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-04 00:14:03.331  5679  5727 I jxcore-log: 
11-04 00:14:03.331  5679  5727 I jxcore-log: 2016-11-03 23:14:03 - WARN testUtils: 'myNameCallback not set!'
11-04 00:14:03.331  5679  5727 I jxcore-log: 
,11-04 00:14:05.355  5679  5727 I jxcore-log: 2016-11-03 23:14:05 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-04 00:14:05.355  5679  5727 I jxcore-log: 
,11-04 00:14:05.357  5679  5727 I jxcore-log: 2016-11-03 23:14:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-04 00:14:05.357  5679  5727 I jxcore-log: 
,11-04 00:14:05.696  5679  5727 I jxcore-log: 2016-11-03 23:14:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-04 00:14:05.696  5679  5727 I jxcore-log: 
,11-04 00:14:05.709  5679  5727 I jxcore-log: 2016-11-03 23:14:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-04 00:14:05.709  5679  5727 I jxcore-log: 
,11-04 00:14:06.836  5679  5727 I jxcore-log: 2016-11-03 23:14:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-04 00:14:06.836  5679  5727 I jxcore-log: 
,11-04 00:14:07.023  5679  5727 I jxcore-log: 2016-11-03 23:14:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-04 00:14:07.023  5679  5727 I jxcore-log: 
,11-04 00:14:07.028  5679  5727 I jxcore-log: 2016-11-03 23:14:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-04 00:14:07.028  5679  5727 I jxcore-log: 
,11-04 00:14:07.033  5679  5727 I jxcore-log: 2016-11-03 23:14:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-04 00:14:07.033  5679  5727 I jxcore-log: 
,11-04 00:14:07.516  5679  5727 I jxcore-log: 2016-11-03 23:14:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-04 00:14:07.516  5679  5727 I jxcore-log: 
,11-04 00:14:07.561  5679  5727 I jxcore-log: 2016-11-03 23:14:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-04 00:14:07.561  5679  5727 I jxcore-log: 
,11-04 00:14:07.574  5679  5727 I jxcore-log: 2016-11-03 23:14:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-04 00:14:07.574  5679  5727 I jxcore-log: 
,11-04 00:14:07.578  5679  5727 I jxcore-log: 2016-11-03 23:14:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-04 00:14:07.578  5679  5727 I jxcore-log: 
,11-04 00:14:07.847  5679  5727 I jxcore-log: 2016-11-03 23:14:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-04 00:14:07.847  5679  5727 I jxcore-log: 
,11-04 00:14:07.972  5679  5727 I jxcore-log: 2016-11-03 23:14:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-04 00:14:07.972  5679  5727 I jxcore-log: 
,11-04 00:14:08.348  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-04 00:14:08.348  5679  5727 I jxcore-log: 
,11-04 00:14:08.356  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-04 00:14:08.356  5679  5727 I jxcore-log: 
,11-04 00:14:08.360  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-04 00:14:08.360  5679  5727 I jxcore-log: 
,11-04 00:14:08.365  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-04 00:14:08.365  5679  5727 I jxcore-log: 
,11-04 00:14:08.371  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-04 00:14:08.371  5679  5727 I jxcore-log: 
,11-04 00:14:08.397  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-04 00:14:08.397  5679  5727 I jxcore-log: 
,11-04 00:14:08.432  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-04 00:14:08.432  5679  5727 I jxcore-log: 
,11-04 00:14:08.440  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-04 00:14:08.440  5679  5727 I jxcore-log: 
,11-04 00:14:08.446  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-04 00:14:08.446  5679  5727 I jxcore-log: 
,11-04 00:14:08.462  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-04 00:14:08.462  5679  5727 I jxcore-log: 
,11-04 00:14:08.466  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-04 00:14:08.466  5679  5727 I jxcore-log: 
,11-04 00:14:08.472  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-04 00:14:08.472  5679  5727 I jxcore-log: 
,11-04 00:14:08.477  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-04 00:14:08.477  5679  5727 I jxcore-log: 
,11-04 00:14:08.490  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-04 00:14:08.490  5679  5727 I jxcore-log: 
,11-04 00:14:08.507  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-04 00:14:08.507  5679  5727 I jxcore-log: 
,11-04 00:14:08.522  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-04 00:14:08.522  5679  5727 I jxcore-log: 
,11-04 00:14:08.532  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-04 00:14:08.532  5679  5727 I jxcore-log: 
,11-04 00:14:08.555  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-04 00:14:08.555  5679  5727 I jxcore-log: 
,11-04 00:14:08.566  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-04 00:14:08.566  5679  5727 I jxcore-log: 
,11-04 00:14:08.579  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-04 00:14:08.579  5679  5727 I jxcore-log: 
,11-04 00:14:08.590  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-04 00:14:08.590  5679  5727 I jxcore-log: 
,11-04 00:14:08.597  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-04 00:14:08.597  5679  5727 I jxcore-log: 
,11-04 00:14:08.618  5679  5727 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-04 00:14:08.620  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - INFO testUtils: 'BLE multiple advertisement supported'
11-04 00:14:08.620  5679  5727 I jxcore-log: 
,11-04 00:14:08.704  5679  5727 I jxcore-log: 2016-11-03 23:14:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:08.704  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:08.704  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:08.704  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:08.704  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:08.704  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:08.704  5679  5727 I jxcore-log: 
,11-04 00:14:09.043  5679  5727 I jxcore-log: 2016-11-03 23:14:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:09.043  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:09.043  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:09.043  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:09.043  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:09.043  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:09.043  5679  5727 I jxcore-log: 
,11-04 00:14:09.046  5679  5727 I jxcore-log: 2016-11-03 23:14:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:09.046  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:09.046  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:09.046  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:09.046  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:09.046  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:09.046  5679  5727 I jxcore-log: 
,11-04 00:14:09.598  5679  5727 I jxcore-log: 2016-11-03 23:14:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:09.598  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:09.598  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:09.598  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:09.598  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:09.598  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:09.598  5679  5727 I jxcore-log: 
,11-04 00:14:09.601  5679  5727 I jxcore-log: 2016-11-03 23:14:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:09.601  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:09.601  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:09.601  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:09.601  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:09.601  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:09.601  5679  5727 I jxcore-log: 
,11-04 00:14:10.250  5679  5727 I jxcore-log: 2016-11-03 23:14:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:10.250  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:10.250  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:10.250  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:10.250  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:10.250  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:10.250  5679  5727 I jxcore-log: 
,11-04 00:14:10.253  5679  5727 I jxcore-log: 2016-11-03 23:14:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:10.253  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:10.253  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:10.253  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:10.253  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:10.253  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:10.253  5679  5727 I jxcore-log: 
,11-04 00:14:11.293  5679  5727 I jxcore-log: 2016-11-03 23:14:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:11.293  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:11.293  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:11.293  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:11.293  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:11.293  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:11.293  5679  5727 I jxcore-log: 
,11-04 00:14:11.302  5679  5727 I jxcore-log: 2016-11-03 23:14:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:11.302  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:11.302  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:11.302  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:11.302  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:11.302  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:11.302  5679  5727 I jxcore-log: 
,11-04 00:14:12.340  5679  5727 I jxcore-log: 2016-11-03 23:14:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:12.340  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:12.340  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:12.340  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:12.340  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:12.340  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:12.340  5679  5727 I jxcore-log: 
,11-04 00:14:12.344  5679  5727 I jxcore-log: 2016-11-03 23:14:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:12.344  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:12.344  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:12.344  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:12.344  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:12.344  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:12.344  5679  5727 I jxcore-log: 
,11-04 00:14:13.375  5679  5727 I jxcore-log: 2016-11-03 23:14:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:13.375  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:13.375  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:13.375  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:13.375  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:13.375  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:13.375  5679  5727 I jxcore-log: 
,11-04 00:14:13.379  5679  5727 I jxcore-log: 2016-11-03 23:14:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:13.379  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:13.379  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:13.379  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:13.379  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:13.379  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:13.379  5679  5727 I jxcore-log: 
,11-04 00:14:14.413  5679  5727 I jxcore-log: 2016-11-03 23:14:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:14.413  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:14.413  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:14.413  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:14.413  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:14.413  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:14.413  5679  5727 I jxcore-log: 
,11-04 00:14:14.419  5679  5727 I jxcore-log: 2016-11-03 23:14:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:14.419  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:14.419  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:14.419  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:14.419  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:14.419  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:14.419  5679  5727 I jxcore-log: 
,11-04 00:14:15.452  5679  5727 I jxcore-log: 2016-11-03 23:14:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:15.452  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:15.452  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:15.452  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:15.452  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:15.452  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:15.452  5679  5727 I jxcore-log: 
,11-04 00:14:15.458  5679  5727 I jxcore-log: 2016-11-03 23:14:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:15.458  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:15.458  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:15.458  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:15.458  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:15.458  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:15.458  5679  5727 I jxcore-log: 
,11-04 00:14:16.489  5679  5727 I jxcore-log: 2016-11-03 23:14:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:16.489  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:16.489  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:16.489  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:16.489  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:16.489  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:16.489  5679  5727 I jxcore-log: 
,11-04 00:14:16.494  5679  5727 I jxcore-log: 2016-11-03 23:14:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:16.494  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:16.494  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:16.494  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:16.494  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:16.494  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:16.494  5679  5727 I jxcore-log: 
,11-04 00:14:17.563  5679  5727 I jxcore-log: 2016-11-03 23:14:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:17.563  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:17.563  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:17.563  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:17.563  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:17.563  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:17.563  5679  5727 I jxcore-log: 
,11-04 00:14:17.567  5679  5727 I jxcore-log: 2016-11-03 23:14:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:17.567  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:17.567  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:17.567  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:17.567  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:17.567  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:17.567  5679  5727 I jxcore-log: 
,11-04 00:14:18.599  5679  5727 I jxcore-log: 2016-11-03 23:14:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:18.599  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:18.599  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:18.599  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:18.599  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:18.599  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:18.599  5679  5727 I jxcore-log: 
,11-04 00:14:18.605  5679  5727 I jxcore-log: 2016-11-03 23:14:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:18.605  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:18.605  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:18.605  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:18.605  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:18.605  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:18.605  5679  5727 I jxcore-log: 
,11-04 00:14:18.986   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:14:19.635  5679  5727 I jxcore-log: 2016-11-03 23:14:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:19.635  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:19.635  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:19.635  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:19.635  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:19.635  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:19.635  5679  5727 I jxcore-log: 
,11-04 00:14:19.638  5679  5727 I jxcore-log: 2016-11-03 23:14:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:19.638  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:19.638  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:19.638  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:19.638  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:19.638  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:19.638  5679  5727 I jxcore-log: 
,11-04 00:14:19.987   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:14:20.669  5679  5727 I jxcore-log: 2016-11-03 23:14:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:20.669  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:20.669  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:20.669  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:20.669  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:20.669  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:20.669  5679  5727 I jxcore-log: 
,11-04 00:14:20.675  5679  5727 I jxcore-log: 2016-11-03 23:14:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:20.675  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:20.675  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:20.675  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:20.675  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:20.675  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:20.675  5679  5727 I jxcore-log: 
,11-04 00:14:20.988   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:14:21.703  5679  5727 I jxcore-log: 2016-11-03 23:14:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:21.703  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:21.703  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:21.703  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:21.703  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:21.703  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:21.703  5679  5727 I jxcore-log: 
,11-04 00:14:21.706  5679  5727 I jxcore-log: 2016-11-03 23:14:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:21.706  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:21.706  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:21.706  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:21.706  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:21.706  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:21.706  5679  5727 I jxcore-log: 
,11-04 00:14:21.989   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:14:22.734  5679  5727 I jxcore-log: 2016-11-03 23:14:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 00:14:22.734  5679  5727 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 00:14:22.734  5679  5727 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 00:14:22.734  5679  5727 I jxcore-log: emit@events.js:82:1
11-04 00:14:22.734  5679  5727 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 00:14:22.734  5679  5727 I jxcore-log: emit@events.js:82:1'
11-04 00:14:22.734  5679  5727 I jxcore-log: 
,11-04 00:14:22.745  5679  5727 E jxcore  : Error!: error is undefined
11-04 00:14:22.745  5679  5727 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-04 00:14:22.748  5679  5727 I jxcore-log: 2016-11-03 23:14:22 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-04 00:14:22.748  5679  5727 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-04 00:14:22.748  5679  5727 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-04 00:14:22.748  5679  5727 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-04 00:14:22.748  5679  5727 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-04 00:14:22.748  5679  5727 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-04 00:14:22.748  5679  5727 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-04 00:14:22.748  5679  5727 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-04 00:14:22.750  5679  5727 I jxcore-log: 2016-11-03 23:14:22 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-04 00:14:22.750  5679  5727 I jxcore-log: 
,11-04 00:14:22.751  5679  5727 E jxcore-log: TypeError: 
11-04 00:14:22.752  5679  5727 E jxcore-log: error is undefined
11-04 00:14:22.752  5679  5727 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-04 00:14:22.752  5679  5727 E jxcore-log: 
,11-04 00:14:22.824   930  3451 I WindowState: WIN DEATH: Window{22a3fa7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-04 00:14:22.824   930  4043 D GraphicsStats: Buffer count: 2
11-04 00:14:22.824   930  3020 D WifiService: Client connection lost with reason: 4
,11-04 00:14:22.838   529   529 I Zygote  : Process 5679 exited cleanly (139)
,11-04 00:14:22.840   930   940 I ActivityManager: Process com.test.thalitest (pid 5679) has died
,11-04 00:14:22.853   930   940 I ActivityManager: Start proc 6067:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-04 00:14:22.924  6067  6067 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-04 00:14:22.943  6067  6067 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-04 00:14:22.948  6067  6067 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1865-1867)
,11-04 00:14:22.949  6067  6067 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 00:14:22.958  6067  6067 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2839180}
,11-04 00:14:22.958  6067  6067 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 00:14:22.958  6067  6067 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 00:14:22.962  6067  6067 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 00:14:22.962  6067  6067 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 00:14:22.972  6067  6067 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 00:14:22.980  6067  6067 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 00:14:22.980  6067  6067 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 00:14:22.980  6067  6067 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 00:14:22.980  6067  6067 I Adreno  : Build Date                       : 12/06/15
11-04 00:14:22.980  6067  6067 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 00:14:22.980  6067  6067 I Adreno  : Local Branch                     : mybranch17112971
11-04 00:14:22.980  6067  6067 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 00:14:22.980  6067  6067 I Adreno  : Remote Branch                    : NONE
11-04 00:14:22.980  6067  6067 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 00:14:22.990   602   602 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 00:14:23.013   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@63b9435:true
,11-04 00:14:23.027  3472  3472 W Binder_5: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[15792]" dev="sockfs" ino=15792 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 00:14:23.027  3472  3472 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[15792]" dev="sockfs" ino=15792 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 00:14:23.039  6067  6067 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 00:14:23.046  6067  6067 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 00:14:23.072  6067  6103 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-04 00:14:23.071  3472  3472 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33471]" dev="sockfs" ino=33471 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 00:14:23.071  3472  3472 W Binder_5: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33471]" dev="sockfs" ino=33471 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 00:14:23.074  3449  3449 W Binder_5: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[15804]" dev="sockfs" ino=15804 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 00:14:23.074  3449  3449 W Binder_5: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[15804]" dev="sockfs" ino=15804 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 00:14:23.080  6067  6090 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 00:14:23.107  6067  6103 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 00:14:23.119   930  4043 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5679 uid 10077
,11-04 00:14:23.117  4043  4043 W Binder_C: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[35899]" dev="sockfs" ino=35899 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 00:14:23.117  4043  4043 W Binder_C: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[35899]" dev="sockfs" ino=35899 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 00:14:23.117  3451  3451 W Binder_7: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[35898]" dev="sockfs" ino=35898 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 00:14:23.117  3451  3451 W Binder_7: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[35898]" dev="sockfs" ino=35898 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 00:14:23.122  3675  3675 I Keyboard.Facilitator: onFinishInput()
,11-04 00:14:23.141   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +271ms (total +299ms)
,11-04 00:14:23.144  6067  6067 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6067
,11-04 00:14:23.206  6067  6067 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 00:14:23.265  6065  6065 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-04 00:14:23.280  6065  6065 D AndroidRuntime: CheckJNI is OFF
,11-04 00:14:23.301  6065  6065 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-04 00:14:23.325  6065  6065 I Radio-JNI: register_android_hardware_Radio DONE
,11-04 00:14:23.340  6065  6065 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-04 00:14:23.345   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-04 00:14:23.345   930   943 I ActivityManager: Killing 6067:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-04 00:14:23.372   930  3819 D GraphicsStats: Buffer count: 2
11-04 00:14:23.372   930  3844 I WindowState: WIN DEATH: Window{42d4c88 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-04 00:14:23.446   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-04 00:14:23.447   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-04 00:14:23.448   930   943 E ActivityManager: Failure starting process com.test.thalitest
11-04 00:14:23.448   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-04 00:14:23.448   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 00:14:23.448   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 00:14:23.448   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 00:14:23.448   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-04 00:14:23.449   930   943 I ActivityManager:   Force finishing activity ActivityRecord{872055c u0 com.test.thalitest/.MainActivity t68}
11-04 00:14:23.450   930   954 I art     : Starting a blocking GC Explicit
,11-04 00:14:23.457   930  3827 W ActivityManager: Spurious death for ProcessRecord{88a4a46 0:com.test.thalitest/u0a77}, curProc for 6067: null
,11-04 00:14:23.541   930   954 I art     : Explicit concurrent mark sweep GC freed 50425(3MB) AllocSpace objects, 17(340KB) LOS objects, 33% free, 29MB/43MB, paused 1.535ms total 90.414ms
,11-04 00:14:23.561   930   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-04 00:14:23.563  6065  6065 I art     : System.exit called, status: 0
,11-04 00:14:23.563  6065  6065 I AndroidRuntime: VM exiting with result code 0.
,11-04 00:14:23.578   930   954 I ActivityManager: Start proc 6117:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-04 00:14:23.579   930   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-04 00:14:23.584   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-04 00:14:23.588  5956  5956 D BluetoothMapAppObserver: onReceive
11-04 00:14:23.589  5956  5956 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-04 00:14:23.593  3724  4165 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-04 00:14:23.597   930  2998 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-04 00:14:23.598  3675  3675 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-04 00:14:23.622  3675  6128 I Keyboard.Facilitator.DecoderInitializer: run()
,11-04 00:14:23.627  3435  6131 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-04 00:14:23.636  3675  6128 I Decoder : createOrResetDecoder
,11-04 00:14:23.649  3796  3796 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-04 00:14:23.660   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-04 00:14:23.665   930  3819 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6067 uid 10077
,11-04 00:14:23.664  3819  3819 W Binder_8: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[27084]" dev="sockfs" ino=27084 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 00:14:23.664  3819  3819 W Binder_8: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[27084]" dev="sockfs" ino=27084 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 00:14:23.667  3675  3675 I Keyboard.Facilitator: onFinishInput()
,11-04 00:14:23.679  3620  3620 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-04 00:14:23.680  3620  3620 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-04 00:14:23.684   413   413 W kworker/3:2: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 00:14:23.694   413   413 W kworker/3:2: type=1400 audit(0.0:136): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-04 00:14:23.696  4015  6136 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-04 00:14:23.696  4015  6136 D AccountUtils: Clearing selected account for com.test.thalitest
,11-04 00:14:23.711   413   413 W kworker/3:2: type=1400 audit(0.0:137): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 00:14:23.714  3620  3620 I ConfigService: onCreate
,11-04 00:14:23.741  3675  6128 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-04 00:14:23.772  4015  6136 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-04 00:14:23.787   381   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
