#### Test 94852510110513c_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-22 18:28:51.270   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:28:51.788  5540  5540 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-22 18:28:51.793  5540  5540 D AndroidRuntime: CheckJNI is OFF
11-22 18:28:51.821  5540  5540 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-22 18:28:51.853  5540  5540 I Radio-JNI: register_android_hardware_Radio DONE
11-22 18:28:51.867  5540  5540 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-22 18:28:51.871   926  3757 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-22 18:28:51.893  5540  5540 D AndroidRuntime: Shutting down VM
11-22 18:28:51.896  3900  3911 W SearchService: Abort, client detached.
11-22 18:28:51.907  3900  4134 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c557bc7
11-22 18:28:51.907  3900  3900 I HotwordDetector: Closing mic
11-22 18:28:51.908  3900  4146 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-22 18:28:51.925   926  3132 I ActivityManager: Start proc 5549:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-22 18:28:51.984   513  4148 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-22 18:28:51.986   513  4148 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-22 18:28:51.992   513  4148 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-22 18:28:51.992   513  4148 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-22 18:28:51.993   513  2931 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-22 18:28:51.995  3900  4137 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-22 18:28:51.995  3900  4145 I MicroRecognitionRnrImpl: Detection finished
11-22 18:28:52.026  5549  5549 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-22 18:28:52.046  5549  5549 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-22 18:28:52.122  5549  5549 I LibraryLoader: Time to load native libraries: 67 ms (timestamps 5565-5632)
,11-22 18:28:52.122  5549  5549 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-22 18:28:52.164  5549  5549 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5372b18}
11-22 18:28:52.164  5549  5549 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-22 18:28:52.165  5549  5549 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-22 18:28:52.171  5549  5549 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-22 18:28:52.173  5549  5549 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-22 18:28:52.210  5549  5549 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-22 18:28:52.223  5549  5549 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-22 18:28:52.223  5549  5549 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-22 18:28:52.223  5549  5549 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-22 18:28:52.223  5549  5549 I Adreno  : Build Date                       : 12/06/15
11-22 18:28:52.223  5549  5549 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-22 18:28:52.223  5549  5549 I Adreno  : Local Branch                     : mybranch17112971
11-22 18:28:52.223  5549  5549 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-22 18:28:52.223  5549  5549 I Adreno  : Remote Branch                    : NONE
11-22 18:28:52.223  5549  5549 I Adreno  : Reconstruct Branch               : NOTHING
,11-22 18:28:52.271   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:28:52.275   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5291504:true
,11-22 18:28:52.313   406   406 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[30812]" dev="sockfs" ino=30812 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 18:28:52.313   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[30812]" dev="sockfs" ino=30812 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 18:28:52.329  5549  5549 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-22 18:28:52.338  5549  5549 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-22 18:28:52.363   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34838]" dev="sockfs" ino=34838 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 18:28:52.363   406   406 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34838]" dev="sockfs" ino=34838 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 18:28:52.368  5549  5587 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-22 18:28:52.367  3358  3358 W Binder_6: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[24428]" dev="sockfs" ino=24428 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 18:28:52.367  3358  3358 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[24428]" dev="sockfs" ino=24428 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 18:28:52.372  5549  5574 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-22 18:28:52.402  5549  5587 I OpenGLRenderer: Initialized EGL, version 1.4
,11-22 18:28:52.477  2871  2871 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33923]" dev="sockfs" ino=33923 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 18:28:52.477  2871  2871 W Binder_3: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33923]" dev="sockfs" ino=33923 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 18:28:52.480   936   936 W Binder_1: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33922]" dev="sockfs" ino=33922 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 18:28:52.484  3589  3589 I Keyboard.Facilitator: onFinishInput()
11-22 18:28:52.480   936   936 W Binder_1: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33922]" dev="sockfs" ino=33922 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 18:28:52.486   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +583ms
,11-22 18:28:52.519  5549  5549 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5549
,11-22 18:28:52.616  5549  5549 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-22 18:28:52.717   926  2871 I ActivityManager: Killing 5329:com.android.chrome/u0a39 (adj 15): empty #17
,11-22 18:28:52.743   926  2871 I ActivityManager: Killing 5317:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,11-22 18:28:52.775  5549  5589 D jxcore_app_log: JniHelper::setJavaVM(0xf53fc000), pthread_self() = -580912848
,11-22 18:28:52.779  5549  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-22 18:28:52.779  5549  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-22 18:28:52.779  5549  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-22 18:28:52.779  5549  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-22 18:28:52.779  5549  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-22 18:28:52.779  5549  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4ce68f added. We now have 1 listener(s)
,11-22 18:28:52.781  5549  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
11-22 18:28:52.781  5549  5589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:28:52.782  5549  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 18:28:52.782  5549  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-22 18:28:52.784  5549  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@872efa added. We now have 1 listener(s)
11-22 18:28:52.784  5549  5589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 18:28:52.788   926  2910 D WifiService: New client listening to asynchronous messages
,11-22 18:28:52.789  5549  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 18:28:52.789  5549  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-22 18:28:52.789  5549  5589 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-22 18:28:52.789  5549  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-22 18:28:52.789  5549  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-22 18:28:52.789  5549  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-22 18:28:52.789  5549  5589 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-22 18:28:52.791  5549  5589 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-22 18:28:52.892  5549  5549 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-22 18:28:53.271   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:28:53.577  5549  5598 W jxcore-log: Initializing JXcore engine
11-22 18:28:53.578  5549  5598 W jxcore-log: JXcore engine is ready
,11-22 18:28:53.600  5598  5598 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11711 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-22 18:28:53.600  5598  5598 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15481]" dev="sockfs" ino=15481 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-22 18:28:53.600  5598  5598 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5886 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-22 18:28:53.600  5598  5598 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33298]" dev="sockfs" ino=33298 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-22 18:28:53.610  5549  5598 W jxcore-log: Starting JXcore engine
,11-22 18:28:53.660  5549  5598 W jxcore-log: Platform android
11-22 18:28:53.660  5549  5598 W jxcore-log: 
,11-22 18:28:53.660  5549  5598 W jxcore-log: Process ARCH arm
11-22 18:28:53.660  5549  5598 W jxcore-log: 
,11-22 18:28:53.846  5549  5598 I jxcore-log: JXcore Cordova bridge is ready!
11-22 18:28:53.846  5549  5598 I jxcore-log: 
,11-22 18:28:53.847  5549  5598 W jxcore-log: JXcore engine is started
,11-22 18:28:53.860  5549  5589 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-22 18:28:53.867  5549  5549 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-22 18:28:54.272   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:28:55.273   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:28:56.274   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 18:29:02.081   926  2910 D WifiService: New client listening to asynchronous messages
,11-22 18:29:02.085  3900  5599 W CronetSyncConnectionRcs: Upload content type not set.
,11-22 18:29:03.565  5549  5598 I jxcore-log: 2016-11-22 17:29:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-22 18:29:03.565  5549  5598 I jxcore-log: 
,11-22 18:29:03.567  5549  5598 I jxcore-log: 2016-11-22 17:29:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-22 18:29:03.567  5549  5598 I jxcore-log: 
,11-22 18:29:03.573  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-22 18:29:03.574  5549  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 18:29:03.574  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:03.574  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:03.574  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 18:29:03.574  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 18:29:03.574  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 18:29:03.574  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 18:29:03.574  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 18:29:03.574  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 18:29:03.575  5549  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 18:29:03.576  5549  5598 I jxcore-log: 2016-11-22 17:29:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-22 18:29:03.576  5549  5598 I jxcore-log: 
11-22 18:29:03.577  5549  5598 I jxcore-log: 2016-11-22 17:29:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-22 18:29:03.577  5549  5598 I jxcore-log: 
,11-22 18:29:03.824  5549  5598 I jxcore-log: 2016-11-22 17:29:03 - DEBUG UnitTest_app: 'Running unit tests'
11-22 18:29:03.824  5549  5598 I jxcore-log: 
,11-22 18:29:03.825  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 18:29:03.825  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e6542a added. We now have 2 listener(s)
11-22 18:29:03.826  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:29:03.826  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 18:29:03.826  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 18:29:03.826  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:29:03.826  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@632d21b added. We now have 2 listener(s)
11-22 18:29:03.826  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 18:29:03.827  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 18:29:03.828  5549  5598 D executeNativeTests: Running unit tests
,11-22 18:29:03.866  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 18:29:03.866  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 added. We now have 3 listener(s)
11-22 18:29:03.867  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:29:03.867  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 18:29:03.867  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 18:29:03.867  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:29:03.867  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 added. We now have 3 listener(s)
,11-22 18:29:03.867  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 18:29:03.868  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 18:29:03.869  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-22 18:29:03.869  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 18:29:03.869  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 18:29:03.869  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 18:29:03.870  5549  5598 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-22 18:29:03.870  5549  5598 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 18:29:03.870  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 18:29:03.870  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 18:29:03.870  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 18:29:03.870  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 18:29:03.871  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:03.871  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:03.871  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:03.871  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:03.871  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:03.871  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 18:29:03.871  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 removed from the list
11-22 18:29:03.871  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:03.871  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 removed from the list
11-22 18:29:03.871  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 18:29:03.872  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.872  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.872  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.872  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.872  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.872  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:03.872  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:03.872  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:03.873  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:03.873  5549  5598 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-22 18:29:03.874  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 18:29:03.874  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:03.874  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:03.874  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:03.874  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:03.874  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:03.874  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:03.874  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:03.874  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:03.874  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:03.874  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.875  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.875  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.875  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.875  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 18:29:03.875  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:03.875  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:03.875  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 18:29:03.877  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 18:29:03.878  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:03.878  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:03.878  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 18:29:03.878  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:03.878  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:03.878  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:03.878  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:03.878  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:03.878  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:03.878  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.878  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:03.879  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.879  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.879  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.879  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:03.879  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 18:29:03.879  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:03.879  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:03.879  5549  5598 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 18:29:03.881  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 18:29:03.881  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 18:29:03.893  5549  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 18:29:03.893  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:03.893  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:03.893  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 18:29:03.893  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 18:29:03.893  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 18:29:03.893  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 18:29:03.893  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 18:29:03.893  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 18:29:03.894  5549  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 18:29:03.894  5549  5598 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 18:29:03.894  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 18:29:03.894  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 18:29:03.894  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 18:29:03.894  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 18:29:03.894  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 18:29:03.896  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 18:29:03.897  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 18:29:03.899  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 18:29:03.899  5549  5598 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 18:29:03.899  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 18:29:03.901  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.901  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 18:29:03.902  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 18:29:03.902  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 18:29:03.902  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 18:29:03.905  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-22 18:29:03.907  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-22 18:29:03.907  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.907  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 18:29:03.907  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 18:29:03.907  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 18:29:03.907  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 18:29:03.907  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.908  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:29:03.910  4575  4589 D BtGatt.GattService: registerClient() - UUID=11f87c8a-6f70-4f84-9b8a-1c533be19691
11-22 18:29:03.910  4575  4650 D BtGatt.GattService: onClientRegistered() - UUID=11f87c8a-6f70-4f84-9b8a-1c533be19691, clientIf=5
11-22 18:29:03.911  5549  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 18:29:03.913  4575  4798 D BtGatt.GattService: start scan with filters
11-22 18:29:03.921  4575  4653 D BtGatt.ScanManager: handling starting scan
11-22 18:29:03.921  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 18:29:03.921  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.921  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 18:29:03.921  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.921  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 18:29:03.921  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 18:29:03.921  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 18:29:03.922  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 18:29:03.922  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 18:29:03.922  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 18:29:03.922  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 18:29:03.922  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.922  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 18:29:03.922  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:29:03.922  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.922  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.923  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:03.923  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 18:29:03.923  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 18:29:03.923  5549  5598 I io.jxcore.node.ConnectionHelper: start: OK
11-22 18:29:03.924  4575  4653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 18:29:03.928  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:29:03.928  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:29:03.928  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:29:03.928  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 18:29:03.929  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:29:03.934  4575  4650 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 18:29:03.934  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 18:29:03.934  4575  4653 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 18:29:03.941  4575  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 18:29:03.941  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:03.942  4575  4653 D BtGatt.ScanManager: Starting BLE batch scan
11-22 18:29:03.942  4575  4653 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 18:29:03.956  4575  4650 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 18:29:03.956  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:03.964  4575  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 18:29:03.965  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 18:29:04.431  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-22 18:29:04.431  5549  5549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 18:29:04.431  5549  5549 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 18:29:05.202   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 18:29:08.236   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 18:29:08.927  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 18:29:08.927  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:08.928  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 18:29:08.928  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 18:29:08.928  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 18:29:08.928  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:08.928  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 18:29:08.928  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-22 18:29:08.928  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.929  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 18:29:08.929  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 18:29:08.929  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.929  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.930  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.930  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 18:29:08.930  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.931  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:29:08.931  4575  4588 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-22 18:29:08.932  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-22 18:29:08.934  4575  4653 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 18:29:08.934  5549  5598 D BluetoothAdapter: STATE_ON
,11-22 18:29:08.935  4575  4798 D BtGatt.GattService: stopScan() - queue size =1
,11-22 18:29:08.937  4575  4588 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 18:29:08.937  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 18:29:08.938  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.938  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 18:29:08.938  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.938  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.939  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.939  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:08.940  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 18:29:08.940  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.940  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.940  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.940  4575  4575 D BtGatt.ScanManager: awakened up at time 182451
11-22 18:29:08.941  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 18:29:08.941  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 18:29:08.943  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:29:08.943  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.947  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.947  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:29:08.948  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.948  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:08.948  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:08.948  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:29:08.948  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 18:29:08.948  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:29:08.948  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:29:08.948  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:08.948  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 18:29:08.948  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:08.948  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 18:29:08.948  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:08.948  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:08.948  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 18:29:08.948  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:08.948  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 18:29:08,.949  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 18:29:08.949  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 18:29:08.949  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 18:29:08.949  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:29:08.949  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:29:08.949  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 18:29:08.950  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 18:29:08.952  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:29:08.952  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:29:08.952  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 18:29:08.964  4575  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-22 18:29:08.964  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:08.964  4575  4650 D BtGatt.GattService: current time is 182476033467
11-22 18:29:08.965  4575  4650 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -90, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -92, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -83, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -85, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -80, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -87, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-22 18:29:08.967  4575  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-22 18:29:08.968  4575  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-22 18:29:08.969  4575  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-22 18:29:08.969  4575  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-22 18:29:08.969  4575  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 18:29:08.969  4575  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-22 18:29:08.974  4575  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 18:29:08.975  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:08.975  4575  4653 D BtGatt.ScanManager: stopping BLe Batch
,11-22 18:29:08.980  4575  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 18:29:08.980  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:08.980  4575  4653 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 18:29:08.985  4575  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 18:29:08.985  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 18:29:09.450  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 18:29:13.954  5549  5598 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-22 18:29:13.959  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 18:29:13.959  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 18:29:13.973  5549  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 18:29:13.973  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:13.973  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:13.973  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 18:29:13.973  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 18:29:13.973  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 18:29:13.973  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 18:29:13.973  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 18:29:13.973  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 18:29:13.975  5549  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 18:29:13.976  5549  5598 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 18:29:13.976  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 18:29:13.976  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 18:29:13.976  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 18:29:13.976  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 18:29:13.976  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 18:29:13.979  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:29:13.983  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 18:29:13.983  5549  5598 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 18:29:13.983  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 18:29:13.983  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:29:13.987  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:13.987  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 18:29:13.988  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 18:29:13.988  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 18:29:13.988  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 18:29:13.992  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:13.992  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 18:29:13.992  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 18:29:13.992  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 18:29:13.992  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 18:29:13.992  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:13.993  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:29:13.995  4575  4588 D BtGatt.GattService: registerClient() - UUID=f13c236d-ca44-4b35-8a82-2390d2ceb148
11-22 18:29:13.996  4575  4650 D BtGatt.GattService: onClientRegistered() - UUID=f13c236d-ca44-4b35-8a82-2390d2ceb148, clientIf=5
11-22 18:29:13.996  5549  5559 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 18:29:13.996  4575  4589 D BtGatt.GattService: start scan with filters
,11-22 18:29:13.999  4575  4653 D BtGatt.ScanManager: handling starting scan
,11-22 18:29:13.999  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 18:29:13.999  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.000  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 18:29:14.000  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:14.000  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 18:29:14.000  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 18:29:14.000  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.000  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 18:29:14.000  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 18:29:14.001  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.001  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.001  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.001  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.001  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 18:29:14.002  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.005  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.005  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:29:14.005  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.005  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.005  5549  5598 I io.jxcore.node.ConnectionHelper: start: OK
11-22 18:29:14.005  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.007  4575  4650 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-22 18:29:14.007  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 18:29:14.008  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:14.008  5549  5598 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 18:29:14.008  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:14.008  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 18:29:14.008  4575  4653 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 18:29:14.008  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 18:29:14.008  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 18:29:14.008  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:14.008  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 18:29:14.010  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.010  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.010  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.010  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 18:29:14.010  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:29:14.010  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:14.010  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 18:29:14.010  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 18:29:14.011  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.011  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.011  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:14.011  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 18:29:14.011  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.012  5549  5598 D BluetoothAdapter: STATE_ON
,11-22 18:29:14.013  4575  4798 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 18:29:14.013  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 18:29:14.013  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:29:14.014  4575  4589 D BtGatt.GattService: stopScan() - queue size =1
11-22 18:29:14.014  4575  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 18:29:14.015  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:14.015  4575  4588 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 18:29:14.015  4575  4653 D BtGatt.ScanManager: Starting BLE batch scan
11-22 18:29:14.015  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 18:29:14.015  4575  4653 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 18:29:14.015  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.015  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 18:29:14.015  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.015  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.015  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.015  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.016  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 18:29:14.016  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.016  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.016  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.016  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 18:29:14.016  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 18:29:14.016  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:29:14.016  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.018  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.018  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 18:29:14.018  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.018  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.019  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:14.019  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:29:14.019  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 18:29:14.019  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:29:14.019  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:29:14.019  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 18:29:14.019  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 18:29:14.019  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:14.019  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.019  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:14.019  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:14.019  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 18:29:14.019  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:14.019  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 18:29:14.019  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 18:29:14.019  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.019  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.019  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.019  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:29:14.019  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.019  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.021  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.021  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.021  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 18:29:14.021  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.021  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.024  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.025  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.025  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.025  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:14.025  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:14.025  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:14.025  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:14.026  4575  4650 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 18:29:14.026  5549  5598 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-22 18:29:14.026  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:14.028  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 18:29:14.028  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 18:29:14.033  4575  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 18:29:14.033  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 18:29:14.034  4575  4653 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 18:29:14.036  5549  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 18:29:14.036  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:14.036  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:14.036  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 18:29:14.036  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 18:29:14.036  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 18:29:14.036  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 18:29:14.036  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 18:29:14.036  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 18:29:14.038  5549  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 18:29:14.038  5549  5598 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 18:29:14.038  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 18:29:14.038  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 18:29:14.038  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 18:29:14.038  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 18:29:14.038  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 18:29:14.040  4575  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 18:29:14.040  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 18:29:14.040  4575  4650 E BtGatt.ContextMap: Context not found for ID 5
11-22 18:29:14.040  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:29:14.042  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-22 18:29:14.042  5549  5598 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 18:29:14.042  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 18:29:14.043  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:29:14.046  4575  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 18:29:14.046  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:14.046  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.046  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 18:29:14.046  4575  4653 D BtGatt.ScanManager: stopping BLe Batch
,11-22 18:29:14.047  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-22 18:29:14.047  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 18:29:14.047  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 18:29:14.050  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.050  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 18:29:14.050  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-22 18:29:14.050  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 18:29:14.050  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 18:29:14.050  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.051  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:29:14.051  4575  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 18:29:14.052  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:14.052  4575  4653 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 18:29:14.053  4575  4798 D BtGatt.GattService: registerClient() - UUID=42b6ed13-79d3-43af-951b-9742f37b7fe1
11-22 18:29:14.053  4575  4650 D BtGatt.GattService: onClientRegistered() - UUID=42b6ed13-79d3-43af-951b-9742f37b7fe1, clientIf=5
,11-22 18:29:14.053  5549  5559 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-22 18:29:14.054  4575  4588 D BtGatt.GattService: start scan with filters
,11-22 18:29:14.056  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 18:29:14.056  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.056  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 18:29:14.056  4575  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 18:29:14.056  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:14.056  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.056  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 18:29:14.056  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 18:29:14.057  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-22 18:29:14.057  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 18:29:14.057  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 18:29:14.057  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.057  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.057  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.057  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.057  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 18:29:14.057  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.058  4575  4653 D BtGatt.ScanManager: handling starting scan
11-22 18:29:14.059  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.059  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:29:14.060  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.060  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:14.060  5549  5598 I io.jxcore.node.ConnectionHelper: start: OK
11-22 18:29:14.060  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-22 18:29:14.062  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.062  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:29:14.062  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 18:29:14.062  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:29:14.063  4575  4650 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 18:29:14.063  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:14.064  4575  4653 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 18:29:14.068  4575  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-22 18:29:14.068  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:14.068  4575  4653 D BtGatt.ScanManager: Starting BLE batch scan
11-22 18:29:14.068  4575  4653 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 18:29:14.076  4575  4650 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-22 18:29:14.077  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 18:29:14.081  4575  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-22 18:29:14.081  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 18:29:14.296   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 18:29:14.563  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-22 18:29:14.564  5549  5549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 18:29:14.564  5549  5549 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 18:29:16.275   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:29:17.276   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:29:18.277   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:29:19.060  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 18:29:19.060  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:19.061  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 18:29:19.061  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 18:29:19.061  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 18:29:19.061  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:19.061  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 18:29:19.061  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 18:29:19.062  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.062  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 18:29:19.062  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 18:29:19.062  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.063  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.063  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.063  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 18:29:19.063  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.067  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:29:19.067  4575  4589 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-22 18:29:19.068  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 18:29:19.069  4575  4653 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 18:29:19.069  5549  5598 D BluetoothAdapter: STATE_ON,
,11-22 18:29:19.071  4575  4798 D BtGatt.GattService: stopScan() - queue size =1
,11-22 18:29:19.073  4575  4589 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 18:29:19.073  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 18:29:19.074  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.074  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 18:29:19.074  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:19.074  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.074  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.075  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.075  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 18:29:19.075  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.075  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:19.075  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.076  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 18:29:19.076  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 18:29:19.077  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:29:19.077  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:19.078  4575  4575 D BtGatt.ScanManager: awakened up at time 192589
11-22 18:29:19.082  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:19.082  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 18:29:19.082  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.082  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:19.082  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:29:19.083  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:29:19.083  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 18:29:19.083  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 18:29:19.083  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 18:29:19.083  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 18:29:19.083  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-22 18:29:19.083  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 18:29:19.083  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:29:19.083  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:29:19.084  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 18:29:19.084  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 18:29:19.086  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:29:19.086  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:29:19.086  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 18:29:19.094  4575  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-22 18:29:19.094  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:19.095  4575  4650 D BtGatt.GattService: current time is 192606119870
,11-22 18:29:19.095  4575  4650 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -90, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -91, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -87, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 18:29:19.095  4575  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-22 18:29:19.095  4575  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
11-22 18:29:19.096  4575  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-22 18:29:19.096  4575  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 18:29:19.096  4575  4650 E BtGatt.ContextMap: Context not found for ID 5
,11-22 18:29:19.104  4575  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 18:29:19.104  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:19.104  4575  4653 D BtGatt.ScanManager: stopping BLe Batch
11-22 18:29:19.109  4575  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 18:29:19.109  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:29:19.110  4575  4653 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 18:29:19.115  4575  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 18:29:19.115  4575  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 18:29:19.278   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:29:19.584  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 18:29:19.585  5549  5549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:19.585  5549  5549 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 18:29:20.279   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:29:21.280   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 18:29:24.084  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 18:29:24.084  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:24.084  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:24.084  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:24.085  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 18:29:24.085  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:29:24.085  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:24.085  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:24.086  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.086  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.086  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:24.086  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 18:29:24.090  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.090  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:24.094  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:24.095  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.095  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:24.095  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:24.095  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:24.095  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 18:29:24.095  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.098  5549  5598 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-22 18:29:24.101  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:24.101  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 18:29:24.101  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:24.102  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:24.102  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:24.102  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:24.102  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 18:29:24.103  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.103  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:24.103  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.103  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:24.106  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.107  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.107  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:24.107  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:24.107  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:24.107  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.108  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:24.111  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-22 18:29:24.111  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 18:29:24.111  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:24.111  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 18:29:24.112  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:24.112  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:24.112  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
,11-22 18:29:24.112  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.112  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:24.112  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:24.113  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.113  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.116  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.117  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:24.117  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.117  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:24.117  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:24.117  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.118  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:24.120  5549  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-22 18:29:24.120  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:24.121  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 18:29:24.121  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:24.121  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:24.122  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:24.122  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
,11-22 18:29:24.122  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.122  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:24.123  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:24.123  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.123  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:24.125  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:24.125  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.125  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.126  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:24.126  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:24.126  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.126  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:24.126  5549  5598 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-22 18:29:24.127  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:24.127  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:24.127  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:24.127  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:24.127  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:24.127  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:24.127  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 18:29:24.127  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.127  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:24.127  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.127  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.129  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.130  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.130  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.130  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:24.130  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 18:29:24.130  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.130  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.131  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-22 18:29:24.131  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 18:29:24.131  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 18:29:24.132  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 18:29:24.132  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 18:29:24.132  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 18:29:24.132  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 18:29:24.132  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-22 18:29:24.132  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 18:29:24.132  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:24.133  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:24.133  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:24.133  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:24.133  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:24.133  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:24.133  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.133  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.133  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:24.133  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.134  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:24.136  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:24.136  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.136  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.136  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:24.136  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:24.136  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.136  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:24.137  5549  5598 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 18:29:24.137  5549  5598 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 18:29:24.137  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-22 18:29:24.142  5549  5598 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-22 18:29:24.142  5549  5598 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-22 18:29:24.143  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 18:29:24.144  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 18:29:24.144  5549  5598 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-22 18:29:24.145  5549  5598 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 18:29:24.145  5549  5598 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,11-22 18:29:24.145  5549  5598 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 18:29:24.145  5549  5598 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 18:29:24.145  5549  5598 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-22 18:29:24.145  5549  5598 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 18:29:24.145  5549  5598 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 18:29:24.145  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-22 18:29:24.150  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-22 18:29:24.151  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,11-22 18:29:24.151  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-22 18:29:24.152  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-22 18:29:24.152  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-22 18:29:24.152  5549  5598 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-22 18:29:24.152  5549  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
,11-22 18:29:24.152  5549  5598 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 18:29:24.153  5549  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-22 18:29:24.153  5549  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-22 18:29:24.153  5549  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-22 18:29:24.153  5549  5598 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-22 18:29:24.154  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 18:29:24.154  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:24.154  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:24.154  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:24.154  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:24.154  5549  5611 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-22 18:29:24.155  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-22 18:29:24.155  5549  5611 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 18:29:24.155  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:24.155  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 18:29:24.155  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:24.155  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:24.156  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.156  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.156  5549  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-22 18:29:24.156  5549  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-22 18:29:24.156  5549  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
11-22 18:29:24.156  5549  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
,11-22 18:29:24.157  5549  5611 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-22 18:29:24.157  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.157  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.157  5549  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-22 18:29:24.157  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.157  5549  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
11-22 18:29:24.157  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:24.157  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 18:29:24.157  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.157  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.153  4588  4588 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33944]" dev="sockfs" ino=33944 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 18:29:24.153  4588  4588 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33944]" dev="sockfs" ino=33944 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 18:29:24.158  5549  5598 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-22 18:29:24.159  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:24.159  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:24.159  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:24.159  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:24.159  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:24.159  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:24.159  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.159  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.160  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 18:29:24.160  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.160  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.161  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.161  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.162  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.163  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:24.163  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:24.164  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.164  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:24.164  5549  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-22 18:29:24.164  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:24.164  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:24.165  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:24.165  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:24.165  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:24.165  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:24.165  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.165  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:24.165  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:24.165  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.165  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.166  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.166  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.166  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.166  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:24.166  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:24.166  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 18:29:24.166  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.167  5549  5598 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-22 18:29:24.167  5549  5598 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-22 18:29:24.167  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 18:29:24.167  5549  5598 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-22 18:29:24.167  5549  5598 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 18:29:24.167  5549  5598 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-22 18:29:24.167  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-22 18:29:24.167  5549  5598 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-22 18:29:24.167  5549  5598 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 18:29:24.167  5549  5598 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 18:29:24.167  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 18:29:24.167  5549  5598 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-22 18:29:24.167  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:24.167  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:24.168  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:24.168  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 18:29:24.168  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:24.168  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:24.168  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.168  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.168  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:24.168  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.168  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.169  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.169  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:24.169  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:24.169  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:24.169  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:24.169  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.169  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.170  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:24.170  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:24.170  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:24.170  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:24.170  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:24.170  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 18:29:26.486   926  5289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=199997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 18:29:28.991   926  2909 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 18:29:29.171  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 18:29:29.171  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:29.171  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:29.171  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:29.172  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
,11-22 18:29:29.172  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:29.172  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:29.172  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 18:29:29.173  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:29.173  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:29.173  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:29.173  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 18:29:29.173  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:29.173  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:29.174  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.174  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:29.177  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:29.177  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.177  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:29.177  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 18:29:29.178  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 18:29:29.178  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:29.178  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:29.181  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-22 18:29:29.182  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 18:29:29.182  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 18:29:29.188  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-22 18:29:29.190  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-22 18:29:29.190  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-22 18:29:29.190  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-22 18:29:29.191  5549  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-22 18:29:29.191  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-22 18:29:29.191  5549  5549 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-22 18:29:29.191  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 18:29:29.192  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:29.193  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-22 18:29:29.193  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-22 18:29:29.193  5549  5613 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 18:29:29.193  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-22 18:29:29.193  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 18:29:29.193  4588  4588 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[30238]" dev="sockfs" ino=30238 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-22 18:29:29.193  4588  4588 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30238]" dev="sockfs" ino=30238 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-22 18:29:29.195  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 18:29:29.195  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-22 18:29:29.196  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:29.196  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:29.196  5549  5549 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-22 18:29:29.196  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 18:29:29.196  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:29.196  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 18:29:29.196  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-22 18:29:29.196  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.197  5549  5613 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-22 18:29:29.198  5549  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-22 18:29:29.198  5549  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-22 18:29:29.199  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.199  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:29:29.199  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.199  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.200  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:29.200  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:29:29.200  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:29.200  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:29:29.200  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:29.200  5549  5549 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-22 18:29:29.200  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:29.200  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:29.200  5549  5549 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:29.200  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:29:29.200  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:29.201  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:29.201  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:29.201  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:29.201  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:29.201  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.201  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:29.204  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.204  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.204  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.204  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 18:29:29.204  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:29.204  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:29.204  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:29.207  5549  5598 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-22 18:29:29.207  5549  5598 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 18:29:29.207  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-22 18:29:29.208  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 18:29:29.208  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 18:29:29.208  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:29:29.208  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:29.208  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:29.208  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:29.208  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:29.209  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:29.209  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:29.209  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:29.209  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:29.209  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.209  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:29.213  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.214  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.214  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.214  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:29.214  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:29.214  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:29.214  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:29.221  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 18:29:29.221  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 18:29:29.221  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 18:29:29.221  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:29.221  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:29.221  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:29.221  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:29.221  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:29.222  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 18:29:29.222  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:29.222  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.223  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.224  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.224  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.224  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:29.224  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:29.224  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:29.224  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 18:29:29.227  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 18:29:29.227  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:29:29.227  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:29:29.228  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:29:29.228  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:29:29.228  5549  5598 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 18:29:29.228  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 18:29:29.228  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:29.228  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:29.228  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.228  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.230  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.230  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:29:29.230  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:29:29.230  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:29:29.231  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:29:29.231  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:29.231  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 18:29:29.233  5549  5598 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-22 18:29:29.233  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 18:29:29.233  5549  5598 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-22 18:29:29.233  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 18:29:29.233  5549  5598 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-22 18:29:29.233  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-22 18:29:29.236  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-22 18:29:29.236  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-22 18:29:29.237  5549  5598 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-22 18:29:29.237  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 18:29:29.238  5549  5598 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-22 18:29:29.238  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-22 18:29:29.238  5549  5598 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-22 18:29:29.238  5549  5598 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-22 18:29:29.240  5549  5598 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-22 18:29:29.240  5549  5598 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-22 18:29:29.241  5549  5598 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-22 18:29:29.241  5549  5598 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-22 18:29:29.241  5549  5598 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-22 18:29:29.241  5549  5598 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-22 18:29:29.243  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 18:29:29.244  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a44ba56 added. We now have 3 listener(s)
11-22 18:29:29.244  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 18:29:29.246  5549  5598 D BluetoothAdapter: enable(): BT is already enabled..!
,11-22 18:29:29.247   926  3744 D WifiService: setWifiEnabled: true pid=5549, uid=10077
11-22 18:29:29.247   926  3744 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 18:29:29.284  4575  4767 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-22 18:29:29.284  4575  4795 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-22 18:29:29.412   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 18:29:29.701  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 18:29:34.254  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 18:29:34.254  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@48dbad7 added. We now have 4 listener(s)
,11-22 18:29:34.254  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 18:29:34.267  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 18:29:34.268  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@48dbad7 removed from the list
,11-22 18:29:34.268  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 18:29:34.270  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 18:29:34.270  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8903fc4 added. We now have 4 listener(s)
,11-22 18:29:34.270  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 18:29:34.272  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 18:29:34.272  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8903fc4 removed from the list
,11-22 18:29:34.272  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:34.273  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 18:29:34.274  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e710ead added. We now have 4 listener(s)
11-22 18:29:34.274  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 18:29:34.277   926   936 D WifiService: setWifiEnabled: false pid=5549, uid=10077
,11-22 18:29:34.277   926   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 18:29:34.282   926  2909 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-22 18:29:34.282   926  2909 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-22 18:29:34.283   926  2909 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 18:29:34.283   926  2909 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 18:29:34.287  4575  4646 D BluetoothAdapterState: Current state: ON, message: 23
11-22 18:29:34.288  4575  4646 D BluetoothAdapterProperties: Setting state to 13
11-22 18:29:34.288  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 18:29:34.288  4575  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-22 18:29:34.288  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 18:29:34.289  4575  4646 D BluetoothAdapterProperties: onBluetoothDisable()
,11-22 18:29:34.294  4575  4646 I BluetoothAdapterState: Entering PendingCommandState
,11-22 18:29:34.297   508   918 D CommandListener: Clearing all IP addresses on wlan0
,11-22 18:29:34.299  4575  4575 D BluetoothMapService: onReceive
11-22 18:29:34.299  4575  4575 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 18:29:34.299  4575  4575 D BluetoothMapService: STATE_TURNING_OFF
11-22 18:29:34.300  4575  4575 D BluetoothMapService: MAP Service closeService in
11-22 18:29:34.300  4575  4575 D BluetoothMapMasInstance0: MAP Service shutdown
11-22 18:29:34.300  4575  4575 D ObexServerSockets0: shutdown(block = true)
11-22 18:29:34.301  4575  4575 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-22 18:29:34.301   926  5290 D DhcpClient: Clearing IP address
11-22 18:29:34.301  4575  4575 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 18:29:34.301  4575  4810 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-22 18:29:34.302  4575  4795 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-22 18:29:34.302  4575  4809 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-22 18:29:34.302  4575  4650 D BluetoothAdapterProperties: Scan Mode:20
11-22 18:29:34.303  4575  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-22 18:29:34.303  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:34.303  5549  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 18:29:34.303  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:34.303  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:34.303  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 18:29:34.303  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 18:29:34.303  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 18:29:34.303  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 18:29:34.303  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 18:29:34.303  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 18:29:34.304  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 18:29:34.304  5549  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 18:29:34.305  5549  5598 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 18:29:34.306   508   918 D CommandListener: Setting iface cfg
11-22 18:29:34.308  4575  4575 I BtOppRfcommListener: stopping Accept Thread
11-22 18:29:34.308  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 18:29:34.308  4575  5217 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-22 18:29:34.309  4575  5217 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-22 18:29:34.311   926  5291 D DhcpClient: Receive thread stopped
11-22 18:29:34.313  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:34.313  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 18:29:34.313  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:34.313  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:34.313  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 18:29:34.313  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 18:29:34.313  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 18:29:34.313  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: <unknown ssid>
11-22 18:29:34.313  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 18:29:34.313  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 18:29:34.314  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:34.314  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: <unknown ssid>
11-22 18:29:34.315  3521  5342 V NativeCrypto: Read error: ssl=0x7f68fde000: I/O error during system call, Connection timed out
,11-22 18:29:34.319  3521  5342 V NativeCrypto: SSL shutdown failed: ssl=0x7f68fde000: I/O error during system call, Broken pipe
,11-22 18:29:34.320  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 18:29:34.323   926  3744 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-22 18:29:34.324   926  5288 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-22 18:29:34.326   926  5288 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-22 18:29:34.326   926  2911 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-22 18:29:34.327   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 18:29:34.328   926  2911 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-22 18:29:34.329   926   939 I ActivityManager: Start proc 5617:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-22 18:29:34.331  4575  4575 D HeadsetService: Received stop request...Stopping profile...
,11-22 18:29:34.333   926  2911 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-22 18:29:34.333   926  2911 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-22 18:29:34.336   926   926 D RttService: SCAN_AVAILABLE : 1
,11-22 18:29:34.336   534   534 E Parcel  : Reading a NULL string not supported here.
11-22 18:29:34.337   926  3018 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 18:29:34.338   926   926 D BluetoothHeadset: Proxy object disconnected
,11-22 18:29:34.338   926   926 D BluetoothHeadset: Proxy object disconnected
,11-22 18:29:34.338   926   926 D BluetoothHeadset: Proxy object disconnected
11-22 18:29:34.339  3078  3090 D BluetoothHeadset: Proxy object disconnected
11-22 18:29:34.339  3712  3923 D BluetoothHeadset: Proxy object disconnected
11-22 18:29:34.340  3078  3078 D HeadsetProfile: Bluetooth service disconnected
11-22 18:29:34.340  4575  4575 D A2dpService: Received stop request...Stopping profile...
11-22 18:29:34.340  4575  4801 D A2dpStateMachine: Exit Disconnected: -1
11-22 18:29:34.342   926   926 D BluetoothA2dp: Proxy object disconnected
11-22 18:29:34.343  4575  4575 D HidService: Received stop request...Stopping profile...
11-22 18:29:34.343  4575  4575 D HidService: Stopping Bluetooth HidService
11-22 18:29:34.343   926  2909 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-22 18:29:34.344  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:34.344  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:34.344  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 18:29:34.344  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:34.344  3078  3078 D BluetoothA2dp: Proxy object disconnected
11-22 18:29:34.344  3078  3078 D BluetoothInputDevice: Proxy object disconnected
11-22 18:29:34.344  3078  3078 D HidProfile: Bluetooth service disconnected
11-22 18:29:34.345  4575  4575 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 18:29:34.346  4575  4575 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-22 18:29:34.346  4575  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 18:29:34.346  4575  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 18:29:34.347  4575  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 18:29:34.347  4575  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 18:29:34.347  4575  4575 D HealthService: Received stop request...Stopping profile...
11-22 18:29:34.347  4575  4650 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-22 18:29:34.348  4575  4575 D PanService: Received stop request...Stopping profile...
11-22 18:29:34.347   926  2911 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-22 18:29:34.349  3078  3078 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 18:29:34.349  3078  3078 D PanProfile: Bluetooth service disconnected
11-22 18:29:34.350   926  2909 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 18:29:34.351  4575  4575 D BluetoothMapService: Received stop request...Stopping profile...
,11-22 18:29:34.351  4575  4575 D BluetoothMapService: stop()
11-22 18:29:34.351  3670  3815 W QCNEJ   : |CORE| network lost: 100
11-22 18:29:34.352  4575  4575 D BluetoothMapAppObserver: deinitObservers()
11-22 18:29:34.352  4575  4575 D BluetoothMapAppObserver: removeReceiver()
11-22 18:29:34.352  3670  3815 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-22 18:29:34.355  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:34.355  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:34.355  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:34.355  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 18:29:34.357  4575  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 18:29:34.357  4575  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 18:29:34.357  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:34.357  4575  4575 V BluetoothAdapterState: isTurningOn()=false
,11-22 18:29:34.357  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:34.357  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:34.357  4575  4767 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 18:29:34.357  4575  4767 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 18:29:34.358  4575  4767 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 18:29:34.358  4575  4767 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 18:29:34.358  4575  4575 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 18:29:34.358  4575  4575 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-22 18:29:34.358  4575  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 18:29:34.359  4575  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 18:29:34.359  4575  4575 D SapService: Received stop request...Stopping profile...
11-22 18:29:34.359  4575  4575 V SapService: stop()
11-22 18:29:34.360  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:34.360  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:34.360  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:34.360  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:34.360  4575  4575 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 18:29:34.360  4575  4650 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 18:29:34.360  4575  4575 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 18:29:34.361  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:34.361  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:34.361  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:34.361  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 18:29:34.361  4575  4575 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 18:29:34.361  4575  4575 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-22 18:29:34.361  3078  3078 D BluetoothMap: Proxy object disconnected
11-22 18:29:34.361  3078  3078 D MapProfile: Bluetooth service disconnected
11-22 18:29:34.362  4575  4575 D BluetoothMapService: MAP Service closeService in
11-22 18:29:34.362  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:34.362  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:34.363  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:34.363  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:34.363  4575  4575 D BluetoothMapService: cleanup()
,11-22 18:29:34.363  4575  4575 D BluetoothMapService: MAP Service closeService in
11-22 18:29:34.363  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:34.364  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:34.364  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:34.364  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:34.364  4575  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 18:29:34.364  4575  4646 D BluetoothAdapterProperties: Setting state to 15
11-22 18:29:34.364  4575  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-22 18:29:34.365  4575  4646 I BluetoothAdapterState: Entering BleOnState
,11-22 18:29:34.365  3078  5310 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 18:29:34.366  3078  3089 D BluetoothMap: onBluetoothStateChange: up=false
11-22 18:29:34.367  3078  3090 D BluetoothPan: onBluetoothStateChange on: false
11-22 18:29:34.367  3078  5310 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-22 18:29:34.370   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 18:29:34.370   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-22 18:29:34.370   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 18:29:34.371  3078  3089 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 18:29:34.371   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 18:29:34.371  3078  3090 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 18:29:34.372  3712  3733 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 18:29:34.372  4575  4646 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-22 18:29:34.372  4575  4646 D BluetoothAdapterProperties: Setting state to 16
11-22 18:29:34.372  4575  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-22 18:29:34.373  4575  4646 D BluetoothAdapterProperties: onBleDisable
11-22 18:29:34.373  4575  4646 I BluetoothAdapterState: Entering PendingCommandState
11-22 18:29:34.373  4575  4647 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-22 18:29:34.374  4575  4767 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-22 18:29:34.374  4575  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 18:29:34.379  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 18:29:34.379  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 18:29:34.379  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:34.379  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:34.379  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 18:29:34.379  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 18:29:34.379  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 18:29:34.379  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 18:29:34.379  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 18:29:34.379  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 18:29:34.379  4575  4650 D BluetoothAdapterProperties: Scan Mode:20
11-22 18:29:34.380  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:34.380  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 18:29:34.380   508   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-22 18:29:34.381  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:29:34.385  5617  5617 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-22 18:29:34.400  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 18:29:34.402   508   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 18:29:34.403   508   918 D CommandListener: Clearing all IP addresses on wlan0
11-22 18:29:34.403   926  2911 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-22 18:29:34.403   926  2911 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 18:29:34.407   926   943 D Tethering: MasterInitialState.processMessage what=3
11-22 18:29:34.407  5172  5172 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@465f184 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-22 18:29:34.408  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:29:34.408   926  2909 D DhcpClient: doQuit
11-22 18:29:34.408   926  2909 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 18:29:34.409   508   918 D TetherController: Setting IP forward enable = 0
,11-22 18:29:34.409   926  5290 D DhcpClient: onQuitting
11-22 18:29:34.409  3387  3387 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-22 18:29:34.411  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 18:29:34.413  3900  3900 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-22 18:29:34.415  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 18:29:34.415  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 18:29:34.415  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:34.415  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:34.415  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 18:29:34.415  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 18:29:34.415  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 18:29:34.415  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 18:29:34.415  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 18:29:34.415  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 18:29:34.416  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:34.417  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 18:29:34.418  4961  4982 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 18:29:34.418  4961  4982 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 18:29:34.418  4961  4982 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-22 18:29:34.419  4961  4982 E SarControlService: no key has been found,reset the power
11-22 18:29:34.419  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 18:29:34.419  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 18:29:34.419  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 18:29:34.420  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 18:29:34.420  4986  4986 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 18:29:34.421  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 18:29:34.421  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 18:29:34.421  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 18:29:34.422  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 18:29:34.422  4986  4986 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-22 18:29:34.425   926  3745 I ActivityManager: Start proc 5642:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-22 18:29:34.427  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000ea03000000000000ffffffff]
11-22 18:29:34.428  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 18:29:34.428  4986  5000 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-22 18:29:34.429  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 18:29:34.429  4961  4972 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-22 18:29:34.434   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8add1e1:true
,11-22 18:29:34.435  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000eb03000000000000ffffffff]
,11-22 18:29:34.438  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-22 18:29:34.438  4986  5000 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-22 18:29:34.439  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 18:29:34.439  4961  4971 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 18:29:34.442  3387  3387 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-22 18:29:34.445  3387  3387 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-22 18:29:34.446   508   911 W SocketClient: write error (Broken pipe)
11-22 18:29:34.446   508   911 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-22 18:29:34.446   508   911 W SocketListener: Error sending broadcast (Broken pipe)
,11-22 18:29:34.461  5617  5617 D LocalBluetoothProfileManager: Adding local MAP profile
,11-22 18:29:34.464  5617  5617 D BluetoothMap: Create BluetoothMap proxy object
,11-22 18:29:34.465   508   918 E Netd    : netlink response contains error (No such file or directory)
,11-22 18:29:34.467   926  2911 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-22 18:29:34.467   508   918 D TetherController: Setting IP forward enable = 0
,11-22 18:29:34.478  5642  5642 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-22 18:29:34.481  5617  5617 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-22 18:29:34.484  3387  3387 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-22 18:29:34.492  3387  3387 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-22 18:29:34.494  5617  5617 D DockEventReceiver: finishStartingService: stopping service
,11-22 18:29:34.503   926  3745 I ActivityManager: Killing 4413:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-22 18:29:34.585  4575  4650 I bt_hci  : shut_down
,11-22 18:29:34.589  4575  4654 D bt_hwcfg: hw_epilog_process
,11-22 18:29:34.589  4575  4654 I bt_vendor: low_power_mode_cb
,11-22 18:29:34.592  4575  4654 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-22 18:29:34.592  4575  4654 I bt_vendor: epilog_cb
11-22 18:29:34.592  4575  4654 I bt_hci  : epilog_finished_callback
,11-22 18:29:34.594  4575  4650 I bt_hci_h4: hal_close
,11-22 18:29:34.595  4575  4650 I bt_userial_vendor: device fd = 54 close
,11-22 18:29:34.598   926  2909 D wifi    : In wifi stop Hal
,11-22 18:29:34.598  4910  4910 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 18:29:34.598   926  2909 D wifi    : halHandle = 0x7f68ff4100, mVM = 0x7f8368d140, mCls = 0x100a02
11-22 18:29:34.599   926  3385 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-22 18:29:34.599   926  3385 D WifiHAL : Got a signal to exit!!!
11-22 18:29:34.599   926  3385 I WifiHAL : Exit wifi_event_loop
11-22 18:29:34.599   926  2909 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-22 18:29:34.600   926  2909 E WifiHAL : Event processing terminated
11-22 18:29:34.600   926  2909 D wifi    : In wifi cleaned up handler
11-22 18:29:34.600   926  2909 I WifiHAL : Internal cleanup completed
11-22 18:29:34.601  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 18:29:34.601  4005  4161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 18:29:34.621   926  3385 D wifi    : set interface wlan0 flags (DOWN)
,11-22 18:29:34.621   926  2909 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 18:29:34.668  5642  5642 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.io.File.exists(File.java:361)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-22 18:29:34.668  5642  5642 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-22 18:29:34.668  5642  5642 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 18:29:34.668  5642  5642 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-22 18:29:34.668  5,642  5642 D StrictMode: 	at com.google.r.e.b(PG:170)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 18:29:34.668  5642  5642 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.k.d(PG:583)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.e.b(PG:170)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 1,8:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 18:29:34.668  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 18:29:34.669  5642  5642 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at java.io.File.exists(File.java:361)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 18:29:34.669  5642  5642 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at java.io.File.exists(File.java:361)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 18:29:34.669  5642  5642 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 18:29:34.669  5642  5642 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 18:29:34.674  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 18:29:34.679  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 18:29:34.688  3798  3798 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 18:29:34.693  3798  3798 D SystemUpdateService: onCreate
11-22 18:29:34.695  3798  3798 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-22 18:29:34.700  5617  5617 D DockEventReceiver: finishStartingService: stopping service
11-22 18:29:34.704  4575  4647 D bt_stack_manager: event_shut_down_stack finished.
,11-22 18:29:34.705  4575  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-22 18:29:34.706  3798  3798 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-22 18:29:34.706  4575  4646 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-22 18:29:34.707  4575  4575 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 18:29:34.708  4575  4575 D BtGatt.GattService: Received stop request...Stopping profile...
11-22 18:29:34.708  4575  4575 D BtGatt.GattService: stop()
11-22 18:29:34.708  4575  4575 D BtGatt.AdvertiseManager: advertise clients cleared
11-22 18:29:34.709  4575  4575 V BluetoothAdapterState: isTurningOff()=false
11-22 18:29:34.709  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:34.709  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:34.709  4575  4575 V BluetoothAdapterState: isBleTurningOff()=true
11-22 18:29:34.710  4575  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 18:29:34.710  4575  4646 D BluetoothAdapterProperties: Setting state to 10
11-22 18:29:34.710  4575  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-22 18:29:34.710  4575  4646 I BluetoothAdapterState: Entering OffState
11-22 18:29:34.711   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-22 18:29:34.717  4575  4575 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-22 18:29:34.717  4575  4575 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 18:29:34.717  4575  4575 I BluetoothServiceJni: cleanupNative: return from cleanup
11-22 18:29:34.718  4575  4647 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-22 18:29:34.730  4575  4647 D bt_stack_manager: event_clean_up_stack finished.
,11-22 18:29:34.742  3798  5314 I iu.UploadsManager: num queued entries: 0
,11-22 18:29:34.743  3798  5314 I iu.UploadsManager: num updated entries: 0
11-22 18:29:34.743  3798  5314 I iu.SyncManager: NEXT; no task
,11-22 18:29:34.752  3798  5680 I SystemUpdateService: active receiver: enabled
,11-22 18:29:34.763  3798  3798 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 18:29:34.764  3798  3798 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 18:29:34.766  4575  4575 I art     : System.exit called, status: 0
,11-22 18:29:34.766  4575  4575 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 18:29:34.776   926  3744 I ActivityManager: Start proc 5684:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-22 18:29:34.781  3798  5680 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 18:29:34.795  3798  5680 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-22 18:29:34.797  3798  5680 I SystemUpdateService: now status is 0 (complete)
11-22 18:29:34.797  3798  5680 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 18:29:34.797  3798  5680 I SystemUpdateService: file has been verified
,11-22 18:29:34.803   926  3358 I ActivityManager: Process com.android.bluetooth (pid 4575) has died
,11-22 18:29:34.812  5684  5684 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-22 18:29:34.814  5684  5684 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 18:29:34.821  5684  5684 D SprintDMHelper: simOperator: 
11-22 18:29:34.821  5684  5684 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 18:29:34.822  3798  5680 I SystemUpdateService: OTA package size = 21989297
,11-22 18:29:34.824   926   943 D Tethering: InitialState.processMessage what=4
,11-22 18:29:34.834   926  3757 I ActivityManager: Start proc 5696:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-22 18:29:34.835   926  3757 I ActivityManager: Killing 5036:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-22 18:29:34.854  3798  5680 I SystemUpdateService: showing system update notification
,11-22 18:29:34.861   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 18:29:34.918   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 18:29:34.956  4910  5710 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 18:29:34.963   926  3745 I ActivityManager: Start proc 5711:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-22 18:29:34.966   926  3745 I ActivityManager: Killing 5362:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-22 18:29:34.968  3798  3798 D SystemUpdateService: onDestroy
,11-22 18:29:34.998   926  3794 I ActivityManager: Killing 5172:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-22 18:29:35.028  5711  5711 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-22 18:29:35.046   926  3794 I ActivityManager: Killing 5408:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-22 18:29:35.143  5642  5671 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-22 18:29:35.151   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e7345cb:true
,11-22 18:29:39.308   926  3794 D WifiService: setWifiEnabled: true pid=5549, uid=10077
,11-22 18:29:39.308   926  3794 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 18:29:39.316   508   918 D SoftapController: Softap fwReload - Ok
,11-22 18:29:39.321   508   918 D CommandListener: Setting iface cfg
11-22 18:29:39.321   508   918 D CommandListener: Trying to bring down wlan0
,11-22 18:29:39.323   508   918 D CommandListener: Clearing all IP addresses on wlan0
,11-22 18:29:39.328   926  2909 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 18:29:39.893   926  2909 D wifi    : set interface wlan0 flags (UP)
,11-22 18:29:39.896   926  2909 I WifiHAL : Initializing wifi
11-22 18:29:39.896   926  2909 I WifiHAL : Creating socket
11-22 18:29:39.897   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-22 18:29:39.900   926  2909 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-22 18:29:39.900   926  2909 D wifi    : Did set static halHandle = 0x7f68ff4100
11-22 18:29:39.900   926  2909 D wifi    : halHandle = 0x7f68ff4100, mVM = 0x7f8368d140, mCls = 0x1936
11-22 18:29:39.901   926  2909 D wifi    : array field set
,11-22 18:29:39.901   926  2909 I WifiNative-HAL: interface[0] = wlan0
,11-22 18:29:39.903   926  5728 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547222405376
11-22 18:29:39.904   926  5728 D wifi    : waitForHalEvents called, vm = 0x7f8368d140, obj = 0x1936, env = 0x7f6b3c9d80
,11-22 18:29:39.970  5729  5729 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 18:29:40.005   926  2909 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-22 18:29:40.011  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:29:40.017  5729  5729 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 18:29:40.050  5729  5729 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 18:29:40.050  5729  5729 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 18:29:40.060   926  2909 D WifiConfigStore: Loading config and enabling all networks 
,11-22 18:29:40.061  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 18:29:40.061  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 18:29:40.061  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:40.061  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:40.061  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 18:29:40.061  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 18:29:40.061  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 18:29:40.061  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 18:29:40.061  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 18:29:40.061  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 18:29:40.062  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:40.062  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 18:29:40.072   926  2909 D WifiConfigStore: loaded 0 passpoint configs
,11-22 18:29:40.073   926  2909 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-22 18:29:40.073   926  2909 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-22 18:29:40.074   926  2909 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-22 18:29:40.074   926  2909 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-22 18:29:40.074   926  2909 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-22 18:29:40.075   926  2909 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-22 18:29:40.075   926  2909 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-22 18:29:40.075   926  2909 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-22 18:29:40.075   926  2909 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-22 18:29:40.075   926  2909 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-22 18:29:40.075   926  2909 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-22 18:29:40.075   926  2909 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-22 18:29:40.077   926  2909 D WifiNative-HAL: Setting external_sim to 1
,11-22 18:29:40.077   926  2909 D wifi    : setting dfs flag to true, 0x7f68ffcc40
11-22 18:29:40.077  4910  4910 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 18:29:40.077   926  2909 D WifiStateMachine: Setting OUI to DA-A1-19
11-22 18:29:40.077   926  2909 D wifi    : setting scan oui 0x7f68ffcc40
,11-22 18:29:40.077   926  2909 D WifiHAL : Sending mac address OUI
,11-22 18:29:40.080   926  2909 E native  : do suspend false
,11-22 18:29:40.086   926  2909 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-22 18:29:40.086   926   926 D RttService: SCAN_AVAILABLE : 3
11-22 18:29:40.086   926  3018 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 18:29:40.090   508   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-22 18:29:40.091   508   918 D CommandListener: Setting iface cfg
11-22 18:29:40.092   926  2901 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
11-22 18:29:40.092   926  2901 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 18:29:40.099   926  2901 D WifiNative-HAL: p2pGetDeviceAddress
,11-22 18:29:40.099   926  2901 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-22 18:29:40.105   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=213616 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-22 18:29:43.155  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 18:29:43.159  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 18:29:43.164  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 18:29:43.219   926  2909 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-22 18:29:43.221   926  2909 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-22 18:29:43.221   926  2909 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 18:29:43.232   926  2909 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 18:29:43.269   926  2909 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 18:29:43.274  5729  5729 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 18:29:43.697  5729  5729 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-22 18:29:43.734  5729  5729 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-22 18:29:43.736  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 18:29:43.745   926  2909 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 18:29:43.746   926  2909 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 18:29:43.746   926  2911 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 18:29:43.765   926  2909 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 18:29:43.777   508   918 D CommandListener: Setting iface cfg
,11-22 18:29:43.783   926  2909 D WifiStateMachine: Start Dhcp Watchdog 2
,11-22 18:29:43.790   926  5737 D DhcpClient: Receive thread started
,11-22 18:29:43.795   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 18:29:43.795   926  2909 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-22 18:29:43.795   926  2911 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-22 18:29:43.877   926  2909 E native  : do suspend false
,11-22 18:29:43.889   926  5736 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 18:29:43.902   926  5737 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172625, domain null
,11-22 18:29:43.902   926  5736 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172625 seconds
,11-22 18:29:43.905   926  5736 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-22 18:29:43.927   926  5737 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 18:29:43.928   926  5736 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-22 18:29:43.932   508   918 D CommandListener: Setting iface cfg
,11-22 18:29:43.936   926  2909 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-22 18:29:43.939   926  5736 D DhcpClient: Scheduling renewal in 86399s
,11-22 18:29:43.948   926  2909 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-22 18:29:43.950   926  2909 D WifiConfigStore: No blacklist allowed without epno enabled
11-22 18:29:43.951   926  2911 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-22 18:29:43.960   926  2909 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-22 18:29:43.969   926  2911 D ConnectivityService: Adding iface wlan0 to network 101
,11-22 18:29:44.003   926  2911 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-22 18:29:44.003   926  2911 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-22 18:29:44.006   926  2911 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-22 18:29:44.007   926  2911 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-22 18:29:44.009   926  2911 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-22 18:29:44.015   926  2911 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 18:29:44.019   926  2911 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-22 18:29:44.019   926  2911 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-22 18:29:44.019   926  2911 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-22 18:29:44.019   926  2911 D ConnectivityService:    accepting network in place of null
11-22 18:29:44.019   926  2909 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-22 18:29:44.019   926  2909 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 18:29:44.020   926  2911 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 18:29:44.040   508   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 18:29:44.057   926  5735 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217568, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 18:29:44.062   508   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 18:29:44.065   926  2911 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-22 18:29:44.065   926  2911 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-22 18:29:44.065  3670  3815 W QCNEJ   : |CORE| network available: 101
11-22 18:29:44.066   926  2911 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-22 18:29:44.067  3670  3815 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-22 18:29:44.067   926   943 D Tethering: MasterInitialState.processMessage what=3
11-22 18:29:44.068  3670  3815 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-22 18:29:44.068  3670  3815 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-22 18:29:44.072  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 18:29:44.073  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 18:29:44.073  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:44.073  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:44.073  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 18:29:44.073  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 18:29:44.073  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 18:29:44.073  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 18:29:44.073  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 18:29:44.073  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 18:29:44.073  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:44.073  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 18:29:44.078  4961  4982 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-22 18:29:44.078  4961  4982 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 18:29:44.078  4961  4982 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-22 18:29:44.078  4961  4982 E SarControlService: no key has been found,reset the power
11-22 18:29:44.078  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 18:29:44.078  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 18:29:44.079  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 18:29:44.079  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 18:29:44.079  4986  4986 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 18:29:44.081  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 18:29:44.081  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-22 18:29:44.081  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 18:29:44.081  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 18:29:44.081  4986  4986 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-22 18:29:44.082  3900  3900 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-22 18:29:44.087  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000ec03000000000000ffffffff]
11-22 18:29:44.087  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 18:29:44.087  4986  5000 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-22 18:29:44.088  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 18:29:44.088  4961  4972 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 18:29:44.088  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000ed03000000000000ffffffff]
11-22 18:29:44.088  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 18:29:44.088  4986  5000 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-22 18:29:44.090  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-22 18:29:44.090  4961  4971 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 18:29:44.091  3798  3798 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-22 18:29:44.093  3798  3798 D SystemUpdateService: onCreate
11-22 18:29:44.096  3798  3798 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 18:29:44.107  3798  3798 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-22 18:29:44.113  3798  5314 I iu.UploadsManager: num queued entries: 0
,11-22 18:29:44.113  3798  5314 I iu.UploadsManager: num updated entries: 0
11-22 18:29:44.113  3798  5314 I iu.SyncManager: NEXT; no task
,11-22 18:29:44.115  3798  5747 I SystemUpdateService: active receiver: enabled
,11-22 18:29:44.118  3798  3798 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 18:29:44.119  3798  3798 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-22 18:29:44.121  5684  5684 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 18:29:44.124  5684  5684 D SprintDMHelper: simOperator: 
11-22 18:29:44.124  5684  5684 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 18:29:44.143   926  5734 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-22 18:29:44.149  3798  5747 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 18:29:44.161  3798  5747 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-22 18:29:44.161  3798  5747 I SystemUpdateService: now status is 0 (complete)
11-22 18:29:44.161  3798  5747 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 18:29:44.161  3798  5747 I SystemUpdateService: file has been verified
11-22 18:29:44.162  3798  5747 I SystemUpdateService: OTA package size = 21989297
,11-22 18:29:44.167  3798  5747 I SystemUpdateService: showing system update notification
,11-22 18:29:44.174   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 18:29:44.175  3798  3798 D SystemUpdateService: onDestroy
,11-22 18:29:44.210   926  5734 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 17:29:44 GMT], X-Android-Received-Millis=[1479835784209], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479835784177]}
,11-22 18:29:44.210   926  2911 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 18:29:44.211   926  2911 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-22 18:29:44.211   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 18:29:44.212   926  2911 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-22 18:29:44.240  4910  5752 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-22 18:29:44.315   926  3745 D WifiService: setWifiEnabled: false pid=5549, uid=10077
11-22 18:29:44.316   926  3745 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 18:29:44.319   926  2909 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-22 18:29:44.319   926  2909 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-22 18:29:44.320   926  2909 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 18:29:44.320   926  2909 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 18:29:44.339   926  5736 D DhcpClient: Clearing IP address
,11-22 18:29:44.340   508   918 D CommandListener: Clearing all IP addresses on wlan0
,11-22 18:29:44.344   508   918 D CommandListener: Setting iface cfg
,11-22 18:29:44.344  3521  5758 V NativeCrypto: Read error: ssl=0x7f68a45d80: I/O error during system call, Connection timed out
11-22 18:29:44.346  3521  5758 V NativeCrypto: SSL shutdown failed: ssl=0x7f68a45d80: I/O error during system call, Broken pipe
,11-22 18:29:44.360   926  3745 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-22 18:29:44.361   926  5734 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-22 18:29:44.361   926  5734 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-22 18:29:44.369   926  2911 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-22 18:29:44.369   926  2911 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-22 18:29:44.370   926  5734 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-22 18:29:44.372   926  5737 D DhcpClient: Receive thread stopped
,11-22 18:29:44.375   534   534 E Parcel  : Reading a NULL string not supported here.
,11-22 18:29:44.379   926   926 D RttService: SCAN_AVAILABLE : 1
11-22 18:29:44.379   926  2911 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-22 18:29:44.380   926  3018 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 18:29:44.382  3670  3815 W QCNEJ   : |CORE| network lost: 101
11-22 18:29:44.382  3670  3815 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-22 18:29:44.385   926  2909 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-22 18:29:44.388   926  2909 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 18:29:44.407   508   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 18:29:44.431   508   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 18:29:44.431   508   918 D CommandListener: Clearing all IP addresses on wlan0
11-22 18:29:44.431   926  2911 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-22 18:29:44.432   926  2911 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-22 18:29:44.434   926   943 D Tethering: MasterInitialState.processMessage what=3
11-22 18:29:44.436  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:44.437  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 18:29:44.437  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:44.437  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:44.437  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 18:29:44.437  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 18:29:44.437  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 18:29:44.437  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 18:29:44.437  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 18:29:44.437  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 18:29:44.437  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:44.437  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 18:29:44.439   926  2909 D DhcpClient: doQuit
11-22 18:29:44.439   926  2909 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-22 18:29:44.439   926  5736 D DhcpClient: onQuitting
,11-22 18:29:44.440  5729  5729 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-22 18:29:44.440  3900  3900 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-22 18:29:44.444  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:44.444  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 18:29:44.444  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:44.444  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:44.444  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 18:29:44.444  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 18:29:44.444  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 18:29:44.444  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 18:29:44.444  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 18:29:44.444  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 18:29:44.444  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:44.444  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 18:29:44.444  4961  4982 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 18:29:44.445  4961  4982 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 18:29:44.445  4961  4982 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-22 18:29:44.445  4961  4982 E SarControlService: no key has been found,reset the power
,11-22 18:29:44.446  3798  3798 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 18:29:44.447  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 18:29:44.447  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 18:29:44.447  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-22 18:29:44.448  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 18:29:44.448  4986  4986 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 18:29:44.449  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 18:29:44.449  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 18:29:44.449  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 18:29:44.450  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 18:29:44.450  4986  4986 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-22 18:29:44.453  3798  3798 D SystemUpdateService: onCreate
,11-22 18:29:44.457  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000ee03000000000000ffffffff]
,11-22 18:29:44.457  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 18:29:44.457  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-22 18:29:44.457  4986  5000 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-22 18:29:44.458  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000ef03000000000000ffffffff]
,11-22 18:29:44.458  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 18:29:44.458  4986  5000 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-22 18:29:44.459  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-22 18:29:44.459  4961  4971 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 18:29:44.460  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-22 18:29:44.460  4961  4972 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 18:29:44.461  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-22 18:29:44.464  3798  3798 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 18:29:44.470  3798  5767 I SystemUpdateService: active receiver: enabled
,11-22 18:29:44.472  3798  3798 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-22 18:29:44.477  3798  5314 I iu.UploadsManager: num queued entries: 0
,11-22 18:29:44.478  3798  5314 I iu.UploadsManager: num updated entries: 0
11-22 18:29:44.479  5729  5729 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-22 18:29:44.481  3798  3798 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 18:29:44.483  3798  3798 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 18:29:44.485  5684  5684 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 18:29:44.488   508   918 E Netd    : netlink response contains error (No such file or directory)
,11-22 18:29:44.489   926  2911 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-22 18:29:44.489   926  2911 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 18:29:44.489  5684  5684 D SprintDMHelper: simOperator: 
11-22 18:29:44.489  5684  5684 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 18:29:44.492  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-22 18:29:44.499  3798  5767 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 18:29:44.503  4910  5771 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 18:29:44.505  3798  5314 I iu.SyncManager: NEXT; no task
,11-22 18:29:44.508  3798  5767 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-22 18:29:44.512  3798  5767 I SystemUpdateService: now status is 0 (complete)
11-22 18:29:44.512  3798  5767 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 18:29:44.512  3798  5767 I SystemUpdateService: file has been verified
11-22 18:29:44.512  3798  5767 I SystemUpdateService: OTA package size = 21989297
,11-22 18:29:44.520  3798  5767 I SystemUpdateService: showing system update notification
,11-22 18:29:44.530   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 18:29:44.532  3798  3798 D SystemUpdateService: onDestroy
,11-22 18:29:44.597   926  2909 D wifi    : In wifi stop Hal
,11-22 18:29:44.597   926  2909 D wifi    : halHandle = 0x7f68ff4100, mVM = 0x7f8368d140, mCls = 0x1936
11-22 18:29:44.599   926  5728 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-22 18:29:44.599   926  5728 D WifiHAL : Got a signal to exit!!!
11-22 18:29:44.599   926  5728 I WifiHAL : Exit wifi_event_loop
11-22 18:29:44.599  4910  4910 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 18:29:44.599  4005  4161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 18:29:44.599  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 18:29:44.600   926  2909 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-22 18:29:44.600   926  2909 E WifiHAL : Event processing terminated
,11-22 18:29:44.600   926  2909 D wifi    : In wifi cleaned up handler
11-22 18:29:44.600   926  2909 I WifiHAL : Internal cleanup completed
,11-22 18:29:44.627   926  5728 D wifi    : set interface wlan0 flags (DOWN)
,11-22 18:29:44.628   926  2909 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 18:29:44.834   926   943 D Tethering: InitialState.processMessage what=4
,11-22 18:29:44.842   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 18:29:45.066   926  2911 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-22 18:29:46.281   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 18:29:46.281   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 18:29:49.356   926   943 I ActivityManager: Start proc 5773:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 18:29:49.445  5773  5773 D AdapterServiceConfig: Adding HeadsetService
,11-22 18:29:49.446  5773  5773 D AdapterServiceConfig: Adding A2dpService
11-22 18:29:49.446  5773  5773 D AdapterServiceConfig: Adding HidService
11-22 18:29:49.446  5773  5773 D AdapterServiceConfig: Adding HealthService
11-22 18:29:49.446  5773  5773 D AdapterServiceConfig: Adding PanService
11-22 18:29:49.446  5773  5773 D AdapterServiceConfig: Adding GattService
,11-22 18:29:49.446  5773  5773 D AdapterServiceConfig: Adding BluetoothMapService
11-22 18:29:49.447  5773  5773 D AdapterServiceConfig: Adding SapService
,11-22 18:29:49.460   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@56b145f:true
,11-22 18:29:49.461  5773  5773 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 18:29:49.464  5773  5773 I bt_bluedroid: init
,11-22 18:29:49.464  5773  5785 I BluetoothAdapterState: Entering OffState
,11-22 18:29:49.466  5773  5786 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-22 18:29:49.466  5773  5786 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 18:29:49.466  5773  5786 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-22 18:29:49.466  5773  5786 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-22 18:29:49.466  5773  5773 I bt_bluedroid: get_profile_interface socket
,11-22 18:29:49.468  5773  5789 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-22 18:29:49.468  5773  5773 I bt_bluedroid: get_profile_interface sdp
,11-22 18:29:49.470  5773  5789 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 18:29:49.474  5773  5784 I bt_bluedroid: config_hci_snoop_log
,11-22 18:29:49.475   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 18:29:49.478  5773  5785 D BluetoothAdapterState: Current state: OFF, message: 0
11-22 18:29:49.478  5773  5785 D BluetoothAdapterProperties: Setting state to 14
,11-22 18:29:49.479  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-22 18:29:49.480  5773  5785 D BluetoothBondStateMachine: make
,11-22 18:29:49.482  5773  5790 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 18:29:49.484  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
,11-22 18:29:49.485  5773  5773 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-22 18:29:49.487  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:29:49.488  5773  5773 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 18:29:49.488  5773  5773 D BtGatt.GattService: Received start request. Starting profile...
,11-22 18:29:49.489  5773  5773 D BtGatt.GattService: start()
11-22 18:29:49.489  5773  5773 I bt_bluedroid: get_profile_interface gatt
,11-22 18:29:49.490  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:29:49.490  5773  5773 D BtGatt.AdvertiseManager: advertise manager created
,11-22 18:29:49.495  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-22 18:29:49.495  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:49.495  5773  5773 V BluetoothAdapterState: isBleTurningOn()=true
11-22 18:29:49.495  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:49.495  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-22 18:29:49.496  5773  5785 I bt_bluedroid: bt_bluedroid
11-22 18:29:49.496  5773  5786 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-22 18:29:49.497  5773  5786 I bt_hci  : start_up
,11-22 18:29:49.502  5773  5786 I bt_vendor: alloc value 0xf40c9871
,11-22 18:29:49.502  5773  5786 I bt_vendor: init
11-22 18:29:49.502  5773  5786 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 18:29:49.502  5773  5786 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 18:29:49.612  5773  5786 D bt_hci  : start_up starting async portion
11-22 18:29:49.613  5773  5793 I bt_hci  : event_finish_startup
11-22 18:29:49.613  5773  5793 I bt_hci_h4: hal_open
11-22 18:29:49.613  5773  5793 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-22 18:29:49.610  5794  5794 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 18:29:49.616  5773  5793 I bt_userial_vendor: device fd = 54 open
,11-22 18:29:49.629  5773  5793 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 18:29:49.632  5773  5793 D bt_hwcfg: Chipset BCM4358A3
,11-22 18:29:49.632  5773  5793 D bt_hwcfg: Target name = [BCM4358A3]
11-22 18:29:49.632  5773  5793 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 18:29:50.026  5773  5793 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 18:29:50.027  5773  5793 D bt_hwcfg: Settlement delay -- 100 ms
11-22 18:29:50.027  5773  5793 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 18:29:50.160  5773  5793 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 18:29:50.161  5773  5793 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-22 18:29:50.162  5773  5793 I bt_hwcfg: vendor lib fwcfg completed
,11-22 18:29:50.162  5773  5793 I bt_vendor: firmware callback
11-22 18:29:50.162  5773  5793 I bt_hci  : firmware_config_callback
11-22 18:29:50.171  5773  5798 I bt_btu  : btu_task pending for preload complete event
,11-22 18:29:50.171  5773  5798 I bt_btu_task: Bluetooth chip preload is complete
11-22 18:29:50.171  5773  5798 I bt_btu  : btu_task received preload complete event
,11-22 18:29:50.178  5773  5798 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 18:29:50.179  5773  5798 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-22 18:29:50.179  5773  5798 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-22 18:29:50.179  5773  5798 I         : BTE_InitTraceLevels -- TRC_AVDT
11-22 18:29:50.179  5773  5798 I         : BTE_InitTraceLevels -- TRC_AVRC
11-22 18:29:50.179  5773  5798 I         : BTE_InitTraceLevels -- TRC_A2D
,11-22 18:29:50.179  5773  5798 I         : BTE_InitTraceLevels -- TRC_BNEP
11-22 18:29:50.180  5773  5798 I         : BTE_InitTraceLevels -- TRC_BTM
11-22 18:29:50.180  5773  5798 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 18:29:50.180  5773  5798 I         : BTE_InitTraceLevels -- TRC_PAN
,11-22 18:29:50.180  5773  5798 I         : BTE_InitTraceLevels -- TRC_SDP
11-22 18:29:50.180  5773  5798 I         : BTE_InitTraceLevels -- TRC_GATT
11-22 18:29:50.180  5773  5798 I         : BTE_InitTraceLevels -- TRC_SMP
11-22 18:29:50.180  5773  5798 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-22 18:29:50.180  5773  5798 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 18:29:50.265  5773  5798 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4047549
11-22 18:29:50.266  5773  5798 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4047549 
,11-22 18:29:50.291  5773  5789 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 18:29:50.293  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 18:29:50.293  5773  5789 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 18:29:50.295  5773  5789 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 18:29:50.297  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
11-22 18:29:50.298  5773  5789 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 18:29:50.298  5773  5789 D bt_hci  : do_postload posting postload work item
11-22 18:29:50.298  5773  5793 I bt_hci  : event_postload
11-22 18:29:50.298  5773  5793 I bt_vendor: sco_config_cb
11-22 18:29:50.298  5773  5793 I bt_hci  : sco_config_callback postload finished.
11-22 18:29:50.300  5773  5789 D bt_bte_conf: Device ID record 1 : primary
,11-22 18:29:50.301  5773  5789 D bt_bte_conf:   vendorId            = 000f
11-22 18:29:50.301  5773  5789 D bt_bte_conf:   vendorIdSource      = 0001
11-22 18:29:50.301  5773  5789 D bt_bte_conf:   product             = 1200
,11-22 18:29:50.301  5773  5789 D bt_bte_conf:   version             = 1436
11-22 18:29:50.301  5773  5789 D bt_bte_conf:   clientExecutableURL = 
11-22 18:29:50.301  5773  5789 D bt_bte_conf:   serviceDescription  = 
11-22 18:29:50.301  5773  5789 D bt_bte_conf:   documentationURL    = 
11-22 18:29:50.301  5773  5789 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 18:29:50.301  5773  5786 D bt_stack_manager: event_start_up_stack finished
11-22 18:29:50.302  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-22 18:29:50.302  5773  5785 D BluetoothAdapterProperties: Setting state to 15
11-22 18:29:50.302  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 18:29:50.303  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 18:29:50.307  5773  5785 I BluetoothAdapterState: Entering BleOnState
11-22 18:29:50.308  5773  5793 I bt_vendor: low_power_mode_cb
11-22 18:29:50.310  5773  5785 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-22 18:29:50.310  5773  5785 D BluetoothAdapterProperties: Setting state to 11
11-22 18:29:50.310  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-22 18:29:50.316  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:29:50.319  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:29:50.320  5773  5773 D HeadsetService: Received start request. Starting profile...
11-22 18:29:50.322  5773  5773 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-22 18:29:50.323  5773  5773 D HeadsetStateMachine: make
,11-22 18:29:50.329  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
,11-22 18:29:50.334  5773  5773 D HeadsetStateMachine: max_hf_connections = 1
,11-22 18:29:50.334  5773  5773 I bt_bluedroid: get_profile_interface handsfree
11-22 18:29:50.334  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-22 18:29:50.334  5773  5789 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-22 18:29:50.337  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:29:50.338  5773  5773 D A2dpService: Received start request. Starting profile...
,11-22 18:29:50.339  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 18:29:50.339  5773  5773 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-22 18:29:50.339  5773  5773 I bt_bluedroid: get_profile_interface avrcp
,11-22 18:29:50.345  5773  5773 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-22 18:29:50.345  5773  5773 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-22 18:29:50.346  5773  5773 D A2dpStateMachine: make
,11-22 18:29:50.347  5773  5773 I bt_bluedroid: get_profile_interface a2dp
,11-22 18:29:50.348  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-22 18:29:50.349  5773  5807 D A2dpStateMachine: Enter Disconnected: -2
,11-22 18:29:50.349  5773  5773 I BluetoothHidServiceJni: classInitNative: succeeds
,11-22 18:29:50.350  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:29:50.351  5617  5617 D BluetoothInputDevice: Proxy object connected
11-22 18:29:50.351  5773  5773 D HidService: Received start request. Starting profile...
11-22 18:29:50.351  5773  5773 I bt_bluedroid: get_profile_interface hidhost
11-22 18:29:50.351  5773  5789 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf402856d
11-22 18:29:50.351  5773  5773 D HidService: setHidService(): set to: null
11-22 18:29:50.352  5617  5617 D HidProfile: Bluetooth service connected
,11-22 18:29:50.352  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 18:29:50.352  5773  5773 I BluetoothHealthServiceJni: classInitNative: succeeds
11-22 18:29:50.353  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 18:29:50.353  5773  5773 D HealthService: Received start request. Starting profile...
,11-22 18:29:50.354  5773  5773 I bt_bluedroid: get_profile_interface health
11-22 18:29:50.355  5773  5773 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-22 18:29:50.355  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:29:50.357  5773  5773 D PanService: Received start request. Starting profile...
,11-22 18:29:50.357  5617  5617 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 18:29:50.357  5773  5773 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 18:29:50.357  5773  5773 I bt_bluedroid: get_profile_interface pan
11-22 18:29:50.357  5773  5789 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-22 18:29:50.357  5617  5617 D PanProfile: Bluetooth service connected
11-22 18:29:50.359  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:29:50.360  5617  5617 D BluetoothMap: Proxy object connected
,11-22 18:29:50.360  5773  5773 D BluetoothMapService: Received start request. Starting profile...
11-22 18:29:50.360  5773  5773 D BluetoothMapService: start()
11-22 18:29:50.360  5617  5617 D MapProfile: Bluetooth service connected
11-22 18:29:50.360  5617  5617 D BluetoothMap: getConnectedDevices()
11-22 18:29:50.361  5617  5617 D BluetoothMap: Bluetooth is Not enabled
,11-22 18:29:50.362  5773  5773 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-22 18:29:50.363  5773  5773 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-22 18:29:50.363  5773  5773 D BluetoothMapAppObserver: createReceiver()
11-22 18:29:50.364  5773  5773 D BluetoothMapAppObserver: initObservers()
11-22 18:29:50.364  5773  5773 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-22 18:29:50.370  5773  5773 V SapService: SapBinder()
,11-22 18:29:50.370  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:29:50.371  5773  5773 D SapService: Received start request. Starting profile...
11-22 18:29:50.371  5773  5773 V SapService: start()
,11-22 18:29:50.374  5773  5773 V BluetoothAdapterState: isTurningOff()=false
,11-22 18:29:50.374  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-22 18:29:50.374  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:50.374  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 18:29:50.375  5773  5805 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-22 18:29:50.375  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-22 18:29:50.375  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-22 18:29:50.375  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:50.375  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:50.375  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-22 18:29:50.376  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-22 18:29:50.376  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 18:29:50.376  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:50.376  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-22 18:29:50.376  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-22 18:29:50.376  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:50.376  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:50.376  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-22 18:29:50.376  5773  5773 V BluetoothAdapterState: isTurningOn()=true
,11-22 18:29:50.376  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:50.376  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:50.377  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-22 18:29:50.377  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-22 18:29:50.377  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 18:29:50.377  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 18:29:50.378  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-22 18:29:50.378  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-22 18:29:50.378  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:50.378  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 18:29:50.378  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-22 18:29:50.378  5773  5785 D BluetoothAdapterProperties: ScanMode =  20
11-22 18:29:50.378  5773  5785 D BluetoothAdapterProperties: State =  11
,11-22 18:29:50.379  5773  5785 D BluetoothAdapterProperties: Setting state to 12
11-22 18:29:50.379  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 18:29:50.379  5773  5785 I BluetoothAdapterState: Entering OnState
11-22 18:29:50.379  3078  3089 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 18:29:50.381  3078  3090 D BluetoothMap: onBluetoothStateChange: up=true
11-22 18:29:50.381  5773  5789 D BluetoothAdapterProperties: Scan Mode:21
11-22 18:29:50.381  5773  5789 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 18:29:50.381  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-22 18:29:50.383  3078  3078 D BluetoothMap: Proxy object connected
11-22 18:29:50.383  3078  3078 D MapProfile: Bluetooth service connected
,11-22 18:29:50.383  3078  3078 D BluetoothMap: getConnectedDevices()
11-22 18:29:50.383  5617  5634 D BluetoothMap: onBluetoothStateChange: up=true
11-22 18:29:50.384  3078  3089 D BluetoothPan: onBluetoothStateChange on: true
11-22 18:29:50.385  5617  5628 D BluetoothPan: onBluetoothStateChange on: true
11-22 18:29:50.386  3078  5310 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-22 18:29:50.386  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 18:29:50.386  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:50.386  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:50.386  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 18:29:50.386  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 18:29:50.386  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 18:29:50.386  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 18:29:50.386  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 18:29:50.386  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 18:29:50.386  3078  3078 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 18:29:50.386  3078  3078 D PanProfile: Bluetooth service connected
11-22 18:29:50.387   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 18:29:50.388  5617  5634 D BluetoothPbap: onBluetoothStateChange: up=true
,11-22 18:29:50.388  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 18:29:50.388  3078  3078 D BluetoothA2dp: Proxy object connected
11-22 18:29:50.388  5773  5773 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 18:29:50.389   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 18:29:50.389   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 18:29:50.389  5773  5773 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-22 18:29:50.389  3078  3090 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 18:29:50.390  5773  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 18:29:50.390  3078  3078 D BluetoothInputDevice: Proxy object connected
11-22 18:29:50.391  3078  3078 D HidProfile: Bluetooth service connected
11-22 18:29:50.391   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 18:29:50.392   926   926 D BluetoothA2dp: Proxy object connected
,11-22 18:29:50.392  5617  5628 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 18:29:50.392  3078  3089 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 18:29:50.392  5773  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 18:29:50.393  3712  3733 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 18:29:50.394  5773  5773 D ObexServerSockets: Succeed to create listening sockets 
11-22 18:29:50.394  5773  5773 D ObexServerSockets0: startAccept()
11-22 18:29:50.394  5773  5773 D ObexServerSockets0: prepareForNewConnect()
11-22 18:29:50.395   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
,11-22 18:29:50.396  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-22 18:29:50.397  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:29:50.398  5617  5617 D LocalBluetoothProfileManager: Adding local A2DP profile
11-22 18:29:50.399  5773  5773 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 18:29:50.399  5773  5773 D BluetoothSdpJni: SDP Create record success - handle: 0
11-22 18:29:50.400  5773  5773 D BluetoothMapService: onReceive
11-22 18:29:50.400  5773  5773 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 18:29:50.400  5773  5773 D BluetoothMapService: STATE_ON
,11-22 18:29:50.400  5773  5814 D ObexServerSockets0: Accepting socket connection...
11-22 18:29:50.400  5773  5813 D ObexServerSockets0: Accepting socket connection...
,11-22 18:29:50.402  5773  5815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 18:29:50.402  5617  5617 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-22 18:29:50.403  5773  5815 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-22 18:29:50.403  5773  5815 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-22 18:29:50.409  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 18:29:50.411  5617  5617 D BluetoothA2dp: Proxy object connected
,11-22 18:29:50.415  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 18:29:50.416  5617  5617 D DockEventReceiver: finishStartingService: stopping service
,11-22 18:29:50.422  5617  5617 D BluetoothPbap: Proxy object connected
,11-22 18:29:50.423  5617  5617 D PbapServerProfile: Bluetooth service connected
,11-22 18:29:50.428  3078  3078 D BluetoothPbap: Proxy object connected
11-22 18:29:50.428  3078  3078 D PbapServerProfile: Bluetooth service connected
11-22 18:29:50.429  5773  5773 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 18:29:50.429  5773  5773 D ObexServerSockets0: prepareForNewConnect()
,11-22 18:29:50.431  5773  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 18:29:50.445  5773  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 18:29:50.446  5773  5823 I BtOppRfcommListener: Accept thread started.
,11-22 18:29:50.489   926   926 D BluetoothHeadset: Proxy object connected
,11-22 18:29:50.489   926   943 D BluetoothHeadset: Proxy object connected
11-22 18:29:50.489   926   926 D BluetoothHeadset: Proxy object connected
11-22 18:29:50.489   926   943 D BluetoothHeadset: Proxy object connected
11-22 18:29:50.489   926   926 D BluetoothHeadset: Proxy object connected
11-22 18:29:50.490  3078  5310 D BluetoothHeadset: Proxy object connected
11-22 18:29:50.490  3078  3078 D HeadsetProfile: Bluetooth service connected
11-22 18:29:50.490  3712  3736 D BluetoothHeadset: Proxy object connected
,11-22 18:29:50.493  3078  3089 D BluetoothHeadset: Proxy object connected
11-22 18:29:50.493  3078  3078 D HeadsetProfile: Bluetooth service connected
11-22 18:29:50.494  3712  3923 D BluetoothHeadset: Proxy object connected
,11-22 18:29:50.507  5617  5628 D BluetoothHeadset: Proxy object connected
,11-22 18:29:50.508  5617  5617 D HeadsetProfile: Bluetooth service connected
,11-22 18:29:52.026   926  2911 D ConnectivityService: handlePromptUnvalidated 101
,11-22 18:29:52.484  3589  3668 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-22 18:29:52.485  3589  3668 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-22 18:29:52.515  3521  3521 I ConfigService: onCreate
,11-22 18:29:54.332  5773  5785 D BluetoothAdapterState: Current state: ON, message: 23
,11-22 18:29:54.332  5773  5785 D BluetoothAdapterProperties: Setting state to 13
,11-22 18:29:54.333  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-22 18:29:54.334  5773  5785 D BluetoothAdapterProperties: onBluetoothDisable()
,11-22 18:29:54.336  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
,11-22 18:29:54.341  5773  5773 D BluetoothMapService: onReceive
,11-22 18:29:54.341  5773  5773 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-22 18:29:54.341  5773  5773 D BluetoothMapService: STATE_TURNING_OFF
11-22 18:29:54.342  5773  5773 D BluetoothMapService: MAP Service closeService in
11-22 18:29:54.343  5773  5773 D BluetoothMapMasInstance0: MAP Service shutdown
,11-22 18:29:54.343  5773  5773 D ObexServerSockets0: shutdown(block = true)
11-22 18:29:54.344  5773  5773 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 18:29:54.344  5773  5813 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-22 18:29:54.344  5773  5814 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-22 18:29:54.345  5773  5773 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 18:29:54.345  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:54.345  5773  5800 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-22 18:29:54.345  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 18:29:54.345  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:29:54.345  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:29:54.345  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 18:29:54.345  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 18:29:54.345  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 18:29:54.345  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 18:29:54.345  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 18:29:54.345  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 18:29:54.346  5773  5773 I BtOppRfcommListener: stopping Accept Thread
11-22 18:29:54.347  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 18:29:54.347  5773  5823 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-22 18:29:54.347  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 18:29:54.347  5773  5823 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-22 18:29:54.348  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
,11-22 18:29:54.349  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-22 18:29:54.349  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 18:29:54.351  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:29:54.357  5773  5773 D HeadsetService: Received stop request...Stopping profile...
,11-22 18:29:54.358   926   926 D BluetoothHeadset: Proxy object disconnected
11-22 18:29:54.359   926   926 D BluetoothHeadset: Proxy object disconnected
11-22 18:29:54.359  5617  5634 D BluetoothHeadset: Proxy object disconnected
11-22 18:29:54.360   926   926 D BluetoothHeadset: Proxy object disconnected
11-22 18:29:54.360  3078  3090 D BluetoothHeadset: Proxy object disconnected
11-22 18:29:54.361  3712  4034 D BluetoothHeadset: Proxy object disconnected
11-22 18:29:54.364  5773  5773 D A2dpService: Received stop request...Stopping profile...
11-22 18:29:54.364  5773  5807 D A2dpStateMachine: Exit Disconnected: -1
11-22 18:29:54.365   926   926 D BluetoothA2dp: Proxy object disconnected
11-22 18:29:54.369  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:54.369  5773  5773 V BluetoothAdapterState: isTurningOn()=false
,11-22 18:29:54.369  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 18:29:54.369  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:54.369  3078  3078 D HeadsetProfile: Bluetooth service disconnected
11-22 18:29:54.370  5773  5773 D HidService: Received stop request...Stopping profile...
11-22 18:29:54.370  3078  3078 D BluetoothA2dp: Proxy object disconnected
11-22 18:29:54.370  5773  5773 D HidService: Stopping Bluetooth HidService
,11-22 18:29:54.371  3078  3078 D BluetoothInputDevice: Proxy object disconnected
,11-22 18:29:54.371  3078  3078 D HidProfile: Bluetooth service disconnected
11-22 18:29:54.374  5773  5773 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 18:29:54.374  5773  5773 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-22 18:29:54.374  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 18:29:54.374  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 18:29:54.374  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 18:29:54.374  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 18:29:54.374  5773  5789 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-22 18:29:54.374  5773  5773 D HealthService: Received stop request...Stopping profile...
11-22 18:29:54.376  5773  5773 D PanService: Received stop request...Stopping profile...
11-22 18:29:54.377  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:54.377  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:54.377  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:54.377  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:54.379  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-22 18:29:54.379  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 18:29:54.379  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 18:29:54.379  5773  5798 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 18:29:54.379  5773  5798 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 18:29:54.379  5773  5798 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 18:29:54.380  5773  5798 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 18:29:54.380  5773  5773 D BluetoothMapService: Received stop request...Stopping profile...
11-22 18:29:54.380  5773  5773 D BluetoothMapService: stop()
11-22 18:29:54.380  5617  5617 D DockEventReceiver: finishStartingService: stopping service
11-22 18:29:54.380  3078  3078 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 18:29:54.380  3078  3078 D PanProfile: Bluetooth service disconnected
11-22 18:29:54.381  5773  5773 D BluetoothMapAppObserver: deinitObservers()
11-22 18:29:54.381  5773  5773 D BluetoothMapAppObserver: removeReceiver()
11-22 18:29:54.381  5617  5617 D HeadsetProfile: Bluetooth service disconnected
11-22 18:29:54.381  5617  5617 D BluetoothA2dp: Proxy object disconnected
11-22 18:29:54.382  5617  5617 D BluetoothInputDevice: Proxy object disconnected
11-22 18:29:54.383  5773  5773 D SapService: Received stop request...Stopping profile...
11-22 18:29:54.383  5773  5773 V SapService: stop()
,11-22 18:29:54.383  3078  3078 D BluetoothMap: Proxy object disconnected
11-22 18:29:54.383  3078  3078 D MapProfile: Bluetooth service disconnected
11-22 18:29:54.384  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:54.384  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:54.384  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:54.384  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:54.385  5773  5773 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 18:29:54.385  5773  5773 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-22 18:29:54.385  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 18:29:54.389  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:54.389  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:54.389  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:54.389  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:54.389  5773  5773 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 18:29:54.389  5773  5789 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 18:29:54.390  5773  5773 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 18:29:54.390  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:54.390  5773  5773 V BluetoothAdapterState: isTurningOn()=false
,11-22 18:29:54.390  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:54.390  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:54.390  5773  5773 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 18:29:54.390  5773  5773 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-22 18:29:54.391  5773  5773 D BluetoothMapService: MAP Service closeService in
11-22 18:29:54.391  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:54.391  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:54.391  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:54.391  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 18:29:54.391  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 18:29:54.392  5773  5773 D BluetoothMapService: cleanup()
11-22 18:29:54.392  5773  5773 D BluetoothMapService: MAP Service closeService in
11-22 18:29:54.392  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-22 18:29:54.392  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:54.392  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:29:54.382  5617  5617 D HidProfile: Bluetooth service disconnected
11-22 18:29:54.392  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:29:54.392  5617  5617 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 18:29:54.392  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 18:29:54.392  5617  5617 D PanProfile: Bluetooth service disconnected
,11-22 18:29:54.392  5773  5785 D BluetoothAdapterProperties: Setting state to 15
11-22 18:29:54.392  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-22 18:29:54.393  5617  5617 D BluetoothMap: Proxy object disconnected
11-22 18:29:54.393  5617  5617 D MapProfile: Bluetooth service disconnected
11-22 18:29:54.394  3078  3089 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 18:29:54.394  5773  5785 I BluetoothAdapterState: Entering BleOnState
11-22 18:29:54.395  5617  5617 D BluetoothPbap: Proxy object disconnected
11-22 18:29:54.395  3078  3090 D BluetoothMap: onBluetoothStateChange: up=false
,11-22 18:29:54.395  5617  5617 D PbapServerProfile: Bluetooth service disconnected
11-22 18:29:54.396  5617  5634 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 18:29:54.396  5617  5628 D BluetoothMap: onBluetoothStateChange: up=false
11-22 18:29:54.397  3078  5310 D BluetoothPan: onBluetoothStateChange on: false
11-22 18:29:54.399  5617  5628 D BluetoothPan: onBluetoothStateChange on: false
11-22 18:29:54.400  3078  3089 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 18:29:54.402  5617  5634 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-22 18:29:54.404   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 18:29:54.404  5617  5628 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 18:29:54.405   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 18:29:54.405   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 18:29:54.405  3078  3090 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 18:29:54.407   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 18:29:54.407  5617  5634 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 18:29:54.407  3078  5310 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-22 18:29:54.408  3712  3733 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 18:29:54.408  5773  5785 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-22 18:29:54.408  5773  5785 D BluetoothAdapterProperties: Setting state to 16
11-22 18:29:54.408  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-22 18:29:54.409  5773  5785 D BluetoothAdapterProperties: onBleDisable
11-22 18:29:54.409  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
11-22 18:29:54.410  5773  5786 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-22 18:29:54.411  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
,11-22 18:29:54.411  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 18:29:54.411  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 18:29:54.412  5773  5798 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-22 18:29:54.412  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 18:29:54.413  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:29:54.416  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 18:29:54.417  5617  5617 D DockEventReceiver: finishStartingService: stopping service
,11-22 18:29:54.627  5773  5789 I bt_hci  : shut_down
,11-22 18:29:54.637  5773  5793 D bt_hwcfg: hw_epilog_process
,11-22 18:29:54.638  5773  5793 I bt_vendor: low_power_mode_cb
,11-22 18:29:54.641  5773  5793 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-22 18:29:54.641  5773  5793 I bt_vendor: epilog_cb
11-22 18:29:54.641  5773  5793 I bt_hci  : epilog_finished_callback
,11-22 18:29:54.647  5773  5789 I bt_hci_h4: hal_close
,11-22 18:29:54.648  5773  5789 I bt_userial_vendor: device fd = 54 close
,11-22 18:29:54.764  5773  5786 D bt_stack_manager: event_shut_down_stack finished.
,11-22 18:29:54.765  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-22 18:29:54.771  5773  5785 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-22 18:29:54.771  5773  5773 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 18:29:54.772  5773  5773 D BtGatt.GattService: Received stop request...Stopping profile...
,11-22 18:29:54.773  5773  5773 D BtGatt.GattService: stop()
11-22 18:29:54.773  5773  5773 D BtGatt.AdvertiseManager: advertise clients cleared
11-22 18:29:54.776  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-22 18:29:54.777  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-22 18:29:54.777  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 18:29:54.777  5773  5773 V BluetoothAdapterState: isBleTurningOff()=true
11-22 18:29:54.777  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 18:29:54.778  5773  5785 D BluetoothAdapterProperties: Setting state to 10
11-22 18:29:54.778  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-22 18:29:54.779  5773  5785 I BluetoothAdapterState: Entering OffState
11-22 18:29:54.781   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-22 18:29:54.796  5773  5773 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-22 18:29:54.796  5773  5773 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 18:29:54.797  5773  5773 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-22 18:29:54.799  5773  5786 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-22 18:29:54.807  5773  5773 I art     : System.exit called, status: 0
,11-22 18:29:54.807  5773  5773 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 18:29:54.833   926  3795 I ActivityManager: Process com.android.bluetooth (pid 5773) has died
,11-22 18:29:56.282   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:29:57.283   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:29:57.548  3521  3521 I ConfigService: onDestroy
,11-22 18:29:58.284   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:29:59.285   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:29:59.329  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 18:29:59.329  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 18:29:59.334  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:59.334  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e710ead removed from the list
,11-22 18:29:59.334  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:59.338  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:29:59.338  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e339430 added. We now have 4 listener(s)
11-22 18:29:59.338  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 18:29:59.340  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:29:59.340  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e339430 removed from the list
11-22 18:29:59.340  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:29:59.342  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:29:59.342  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ce8a9 added. We now have 4 listener(s)
11-22 18:29:59.342  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 18:30:00.286   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:01.037   926   939 I ActivityManager: Start proc 5831:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,11-22 18:30:01.094  5831  5831 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,11-22 18:30:01.117  5831  5831 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
11-22 18:30:01.117  5831  5831 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-22 18:30:01.117  5831  5831 I GAv4    :   adb logcat -s GAv4
,11-22 18:30:01.134  5831  5831 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,11-22 18:30:01.139  5831  5831 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,11-22 18:30:01.157  5831  5846 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,11-22 18:30:01.169   926  3358 I ActivityManager: Killing 3821:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-22 18:30:01.287   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 18:30:04.353  5549  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:30:04.390   926   943 I ActivityManager: Start proc 5849:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 18:30:04.491  5849  5849 D AdapterServiceConfig: Adding HeadsetService
,11-22 18:30:04.492  5849  5849 D AdapterServiceConfig: Adding A2dpService
11-22 18:30:04.492  5849  5849 D AdapterServiceConfig: Adding HidService
,11-22 18:30:04.492  5849  5849 D AdapterServiceConfig: Adding HealthService
,11-22 18:30:04.492  5849  5849 D AdapterServiceConfig: Adding PanService
11-22 18:30:04.493  5849  5849 D AdapterServiceConfig: Adding GattService
11-22 18:30:04.493  5849  5849 D AdapterServiceConfig: Adding BluetoothMapService
11-22 18:30:04.493  5849  5849 D AdapterServiceConfig: Adding SapService
,11-22 18:30:04.507   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b50896:true
,11-22 18:30:04.508  5849  5849 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 18:30:04.511  5849  5849 I bt_bluedroid: init
,11-22 18:30:04.511  5849  5861 I BluetoothAdapterState: Entering OffState
,11-22 18:30:04.514  5849  5862 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-22 18:30:04.514  5849  5862 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 18:30:04.514  5849  5862 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-22 18:30:04.514  5849  5862 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-22 18:30:04.515  5849  5849 I bt_bluedroid: get_profile_interface socket
,11-22 18:30:04.517  5849  5849 I bt_bluedroid: get_profile_interface sdp
11-22 18:30:04.517  5849  5865 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 18:30:04.519  5849  5865 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 18:30:04.522  5849  5860 I bt_bluedroid: config_hci_snoop_log
11-22 18:30:04.524   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 18:30:04.530  5849  5861 D BluetoothAdapterState: Current state: OFF, message: 0
11-22 18:30:04.530  5849  5861 D BluetoothAdapterProperties: Setting state to 14
11-22 18:30:04.530  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-22 18:30:04.531  5849  5861 D BluetoothBondStateMachine: make
,11-22 18:30:04.534  5849  5866 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 18:30:04.536  5849  5861 I BluetoothAdapterState: Entering PendingCommandState
,11-22 18:30:04.538  5849  5849 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-22 18:30:04.540  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 18:30:04.541  5849  5849 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 18:30:04.542  5849  5849 D BtGatt.GattService: Received start request. Starting profile...
11-22 18:30:04.542  5849  5849 D BtGatt.GattService: start()
11-22 18:30:04.542  5849  5849 I bt_bluedroid: get_profile_interface gatt
,11-22 18:30:04.543  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:30:04.543  5849  5849 D BtGatt.AdvertiseManager: advertise manager created
,11-22 18:30:04.549  5849  5849 V BluetoothAdapterState: isTurningOff()=false
,11-22 18:30:04.549  5849  5849 V BluetoothAdapterState: isTurningOn()=false
11-22 18:30:04.549  5849  5849 V BluetoothAdapterState: isBleTurningOn()=true
11-22 18:30:04.549  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:30:04.550  5849  5861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-22 18:30:04.552  5849  5861 I bt_bluedroid: bt_bluedroid
11-22 18:30:04.552  5849  5862 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-22 18:30:04.552  5849  5862 I bt_hci  : start_up
,11-22 18:30:04.558  5849  5862 I bt_vendor: alloc value 0xf40c9871
,11-22 18:30:04.558  5849  5862 I bt_vendor: init
11-22 18:30:04.558  5849  5862 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 18:30:04.558  5849  5862 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 18:30:04.672  5849  5862 D bt_hci  : start_up starting async portion
11-22 18:30:04.673  5849  5869 I bt_hci  : event_finish_startup
,11-22 18:30:04.673  5849  5869 I bt_hci_h4: hal_open
11-22 18:30:04.673  5849  5869 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-22 18:30:04.670  5870  5870 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 18:30:04.676  5849  5869 I bt_userial_vendor: device fd = 54 open
,11-22 18:30:04.694  5849  5869 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 18:30:04.698  5849  5869 D bt_hwcfg: Chipset BCM4358A3
,11-22 18:30:04.699  5849  5869 D bt_hwcfg: Target name = [BCM4358A3]
11-22 18:30:04.699  5849  5869 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 18:30:05.219  5849  5869 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 18:30:05.220  5849  5869 D bt_hwcfg: Settlement delay -- 100 ms
11-22 18:30:05.220  5849  5869 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 18:30:05.354  5849  5869 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 18:30:05.354  5849  5869 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-22 18:30:05.356  5849  5869 I bt_hwcfg: vendor lib fwcfg completed
11-22 18:30:05.357  5849  5869 I bt_vendor: firmware callback
11-22 18:30:05.357  5849  5869 I bt_hci  : firmware_config_callback
,11-22 18:30:05.368  5849  5872 I bt_btu  : btu_task pending for preload complete event
,11-22 18:30:05.368  5849  5872 I bt_btu_task: Bluetooth chip preload is complete
11-22 18:30:05.368  5849  5872 I bt_btu  : btu_task received preload complete event
,11-22 18:30:05.375  5849  5872 I         : BTE_InitTraceLevels -- TRC_HCI
11-22 18:30:05.376  5849  5872 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-22 18:30:05.376  5849  5872 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-22 18:30:05.376  5849  5872 I         : BTE_InitTraceLevels -- TRC_AVDT
11-22 18:30:05.376  5849  5872 I         : BTE_InitTraceLevels -- TRC_AVRC
11-22 18:30:05.376  5849  5872 I         : BTE_InitTraceLevels -- TRC_A2D
11-22 18:30:05.376  5849  5872 I         : BTE_InitTraceLevels -- TRC_BNEP
11-22 18:30:05.376  5849  5872 I         : BTE_InitTraceLevels -- TRC_BTM
,11-22 18:30:05.377  5849  5872 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 18:30:05.377  5849  5872 I         : BTE_InitTraceLevels -- TRC_PAN
11-22 18:30:05.377  5849  5872 I         : BTE_InitTraceLevels -- TRC_SDP
11-22 18:30:05.377  5849  5872 I         : BTE_InitTraceLevels -- TRC_GATT
11-22 18:30:05.377  5849  5872 I         : BTE_InitTraceLevels -- TRC_SMP
,11-22 18:30:05.377  5849  5872 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-22 18:30:05.377  5849  5872 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 18:30:05.478  5849  5872 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4047549
11-22 18:30:05.479  5849  5872 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4047549 
,11-22 18:30:05.502  5849  5865 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 18:30:05.504  5849  5865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 18:30:05.505  5849  5865 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 18:30:05.509  5849  5865 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 18:30:05.512  5849  5865 D BluetoothAdapterProperties: Scan Mode:20
11-22 18:30:05.513  5849  5865 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 18:30:05.513  5849  5865 D bt_hci  : do_postload posting postload work item
11-22 18:30:05.513  5849  5869 I bt_hci  : event_postload
11-22 18:30:05.513  5849  5869 I bt_vendor: sco_config_cb
11-22 18:30:05.513  5849  5869 I bt_hci  : sco_config_callback postload finished.
,11-22 18:30:05.516  5849  5865 D bt_bte_conf: Device ID record 1 : primary
11-22 18:30:05.516  5849  5865 D bt_bte_conf:   vendorId            = 000f
11-22 18:30:05.516  5849  5865 D bt_bte_conf:   vendorIdSource      = 0001
11-22 18:30:05.516  5849  5865 D bt_bte_conf:   product             = 1200
11-22 18:30:05.516  5849  5865 D bt_bte_conf:   version             = 1436
,11-22 18:30:05.516  5849  5865 D bt_bte_conf:   clientExecutableURL = 
11-22 18:30:05.517  5849  5865 D bt_bte_conf:   serviceDescription  = 
11-22 18:30:05.517  5849  5865 D bt_bte_conf:   documentationURL    = 
11-22 18:30:05.517  5849  5865 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-22 18:30:05.517  5849  5862 D bt_stack_manager: event_start_up_stack finished
11-22 18:30:05.518  5849  5861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-22 18:30:05.519  5849  5861 D BluetoothAdapterProperties: Setting state to 15
,11-22 18:30:05.519  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 18:30:05.520  5849  5861 I BluetoothAdapterState: Entering BleOnState
,11-22 18:30:05.525  5849  5861 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-22 18:30:05.525  5849  5861 D BluetoothAdapterProperties: Setting state to 11
11-22 18:30:05.525  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-22 18:30:05.525  5849  5869 I bt_vendor: low_power_mode_cb
,11-22 18:30:05.533  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:30:05.535  5849  5849 D HeadsetService: Received start request. Starting profile...
,11-22 18:30:05.540  5849  5849 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-22 18:30:05.540  5849  5849 D HeadsetStateMachine: make
,11-22 18:30:05.549  5849  5861 I BluetoothAdapterState: Entering PendingCommandState
,11-22 18:30:05.552  5849  5849 D HeadsetStateMachine: max_hf_connections = 1
,11-22 18:30:05.552  5849  5849 I bt_bluedroid: get_profile_interface handsfree
11-22 18:30:05.552  5849  5865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-22 18:30:05.554  5849  5865 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-22 18:30:05.556  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 18:30:05.557  5849  5849 D A2dpService: Received start request. Starting profile...
11-22 18:30:05.557  5849  5849 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-22 18:30:05.558  5849  5849 I bt_bluedroid: get_profile_interface avrcp
,11-22 18:30:05.564  5849  5849 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-22 18:30:05.564  5849  5849 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-22 18:30:05.565  5849  5849 D A2dpStateMachine: make
,11-22 18:30:05.566  5849  5849 I bt_bluedroid: get_profile_interface a2dp
11-22 18:30:05.566  5849  5865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-22 18:30:05.568  5849  5879 D A2dpStateMachine: Enter Disconnected: -2
11-22 18:30:05.569  5849  5849 I BluetoothHidServiceJni: classInitNative: succeeds
,11-22 18:30:05.570  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 18:30:05.570  5849  5849 D HidService: Received start request. Starting profile...
11-22 18:30:05.571  5849  5849 I bt_bluedroid: get_profile_interface hidhost
11-22 18:30:05.571  5849  5849 D HidService: setHidService(): set to: null
11-22 18:30:05.571  5849  5865 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf402856d
,11-22 18:30:05.571  5849  5865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-22 18:30:05.573  5849  5849 I BluetoothHealthServiceJni: classInitNative: succeeds
11-22 18:30:05.574  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:30:05.575  5849  5849 D HealthService: Received start request. Starting profile...
11-22 18:30:05.577  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 18:30:05.577  5849  5849 I bt_bluedroid: get_profile_interface health
,11-22 18:30:05.578  5849  5849 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-22 18:30:05.579  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 18:30:05.580  5849  5849 D PanService: Received start request. Starting profile...
,11-22 18:30:05.580  5849  5849 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 18:30:05.580  5849  5849 I bt_bluedroid: get_profile_interface pan
11-22 18:30:05.581  5849  5865 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-22 18:30:05.583  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:30:05.584  5849  5849 D BluetoothMapService: Received start request. Starting profile...
11-22 18:30:05.584  5849  5849 D BluetoothMapService: start()
,11-22 18:30:05.587  5849  5849 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-22 18:30:05.588  5849  5849 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-22 18:30:05.588  5849  5849 D BluetoothMapAppObserver: createReceiver()
,11-22 18:30:05.589  5849  5849 D BluetoothMapAppObserver: initObservers()
,11-22 18:30:05.589  5849  5849 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-22 18:30:05.597  5849  5849 V SapService: SapBinder()
11-22 18:30:05.597  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 18:30:05.598  5849  5849 D SapService: Received start request. Starting profile...
11-22 18:30:05.598  5849  5849 V SapService: start()
11-22 18:30:05.599  5849  5849 V BluetoothAdapterState: isTurningOff()=false
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isTurningOn()=true
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isTurningOff()=false
,11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isTurningOn()=true
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:30:05.600  5849  5877 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isTurningOff()=false
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isTurningOn()=true
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isTurningOff()=false
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isTurningOn()=true
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:30:05.600  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:30:05.601  5849  5849 V BluetoothAdapterState: isTurningOff()=false
11-22 18:30:05.601  5849  5849 V BluetoothAdapterState: isTurningOn()=true
11-22 18:30:05.601  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 18:30:05.601  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:30:05.601  5849  5849 V BluetoothAdapterState: isTurningOff()=false
11-22 18:30:05.601  5849  5849 V BluetoothAdapterState: isTurningOn()=true
11-22 18:30:05.601  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:30:05.601  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
11-22 18:30:05.602  5849  5849 V BluetoothAdapterState: isTurningOff()=false
11-22 18:30:05.602  5849  5849 V BluetoothAdapterState: isTurningOn()=true
11-22 18:30:05.602  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
11-22 18:30:05.602  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 18:30:05.602  5849  5861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-22 18:30:05.602  5849  5861 D BluetoothAdapterProperties: ScanMode =  20
11-22 18:30:05.602  5849  5861 D BluetoothAdapterProperties: State =  11
11-22 18:30:05.603  5849  5861 D BluetoothAdapterProperties: Setting state to 12
11-22 18:30:05.603  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 18:30:05.603  3078  3089 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 18:30:05.604  5849  5865 D BluetoothAdapterProperties: Scan Mode:21
11-22 18:30:05.604  5849  5865 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 18:30:05.605  5849  5861 I BluetoothAdapterState: Entering OnState
11-22 18:30:05.606  3078  3090 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 18:30:05.610  5617  5634 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 18:30:05.610  5617  5847 D BluetoothMap: onBluetoothStateChange: up=true
11-22 18:30:05.610  3078  3078 D BluetoothMap: Proxy object connected
11-22 18:30:05.610  3078  3078 D MapProfile: Bluetooth service connected
11-22 18:30:05.610  3078  3078 D BluetoothMap: getConnectedDevices()
,11-22 18:30:05.612  3078  3089 D BluetoothPan: onBluetoothStateChange on: true
11-22 18:30:05.613  5617  5634 D BluetoothPan: onBluetoothStateChange on: true
11-22 18:30:05.615  3078  3078 D BluetoothPan: BluetoothPAN Proxy object connected
,11-22 18:30:05.615  3078  3078 D PanProfile: Bluetooth service connected
11-22 18:30:05.615  5849  5849 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 18:30:05.615  3078  5310 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 18:30:05.616  5849  5849 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-22 18:30:05.617  5617  5847 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 18:30:05.617  5849  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 18:30:05.618  5617  5617 D BluetoothMap: Proxy object connected
11-22 18:30:05.618  5617  5617 D MapProfile: Bluetooth service connected
11-22 18:30:05.618  5617  5617 D BluetoothMap: getConnectedDevices()
11-22 18:30:05.619  5849  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 18:30:05.619   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 18:30:05.619  5617  5628 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 18:30:05.620  5849  5849 D ObexServerSockets: Succeed to create listening sockets 
,11-22 18:30:05.620  5849  5849 D ObexServerSockets0: startAccept()
11-22 18:30:05.620  5849  5849 D ObexServerSockets0: prepareForNewConnect()
11-22 18:30:05.621   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 18:30:05.621   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 18:30:05.621  3078  3089 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 18:30:05.622  5849  5849 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 18:30:05.622  5849  5849 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-22 18:30:05.623   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 18:30:05.623  5849  5884 D ObexServerSockets0: Accepting socket connection...
11-22 18:30:05.623  5617  5634 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 18:30:05.624  5849  5885 D ObexServerSockets0: Accepting socket connection...
,11-22 18:30:05.625   926   926 D BluetoothA2dp: Proxy object connected
11-22 18:30:05.625  3078  3078 D BluetoothA2dp: Proxy object connected
11-22 18:30:05.628  3078  3089 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-22 18:30:05.629  3078  3078 D BluetoothInputDevice: Proxy object connected
,11-22 18:30:05.629  3078  3078 D HidProfile: Bluetooth service connected
11-22 18:30:05.629  3712  3736 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 18:30:05.630  5617  5617 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 18:30:05.630  5617  5617 D PanProfile: Bluetooth service connected
11-22 18:30:05.630  5617  5617 D BluetoothA2dp: Proxy object connected
11-22 18:30:05.631   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-22 18:30:05.632  5849  5849 D BluetoothMapService: onReceive
,11-22 18:30:05.632  5849  5849 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 18:30:05.632  5849  5849 D BluetoothMapService: STATE_ON
,11-22 18:30:05.632  5617  5617 D BluetoothInputDevice: Proxy object connected
11-22 18:30:05.632  5617  5617 D HidProfile: Bluetooth service connected
,11-22 18:30:05.636  5849  5889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 18:30:05.637  5849  5889 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-22 18:30:05.637  5849  5889 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-22 18:30:05.638  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 18:30:05.645  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 18:30:05.646  5617  5617 D DockEventReceiver: finishStartingService: stopping service
,11-22 18:30:05.652  5617  5617 D BluetoothPbap: Proxy object connected
,11-22 18:30:05.652  5617  5617 D PbapServerProfile: Bluetooth service connected
,11-22 18:30:05.657  5849  5849 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-22 18:30:05.658  5849  5849 D ObexServerSockets0: prepareForNewConnect()
,11-22 18:30:05.659  5849  5893 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 18:30:05.665  3078  3078 D BluetoothPbap: Proxy object connected
11-22 18:30:05.665  3078  3078 D PbapServerProfile: Bluetooth service connected
,11-22 18:30:05.675  5849  5897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 18:30:05.676  5849  5897 I BtOppRfcommListener: Accept thread started.
,11-22 18:30:05.712   926   926 D BluetoothHeadset: Proxy object connected
11-22 18:30:05.712   926   926 D BluetoothHeadset: Proxy object connected
,11-22 18:30:05.713  5617  5847 D BluetoothHeadset: Proxy object connected
,11-22 18:30:05.713   926   926 D BluetoothHeadset: Proxy object connected
11-22 18:30:05.714  3078  5310 D BluetoothHeadset: Proxy object connected
11-22 18:30:05.714  3078  3078 D HeadsetProfile: Bluetooth service connected
11-22 18:30:05.714  3712  3923 D BluetoothHeadset: Proxy object connected
11-22 18:30:05.716  5617  5617 D HeadsetProfile: Bluetooth service connected
,11-22 18:30:05.719   926   943 D BluetoothHeadset: Proxy object connected
,11-22 18:30:05.721   926   943 D BluetoothHeadset: Proxy object connected
,11-22 18:30:05.722   926   943 D BluetoothHeadset: Proxy object connected
,11-22 18:30:05.729  3078  3090 D BluetoothHeadset: Proxy object connected
,11-22 18:30:05.730  3078  3078 D HeadsetProfile: Bluetooth service connected
,11-22 18:30:05.731  3712  4034 D BluetoothHeadset: Proxy object connected
,11-22 18:30:06.288   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:07.289   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:08.290   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:09.291   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:09.370  5549  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 18:30:09.370  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:30:09.370  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:30:09.370  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 18:30:09.370  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 18:30:09.370  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 18:30:09.370  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 18:30:09.370  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 18:30:09.370  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 18:30:09.376  5549  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 18:30:09.377  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:09.377  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ce8a9 removed from the list
11-22 18:30:09.378  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 18:30:09.382  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:30:09.383  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@488be2e added. We now have 4 listener(s)
11-22 18:30:09.383  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 18:30:09.387   926  3794 D WifiService: setWifiEnabled: false pid=5549, uid=10077
,11-22 18:30:09.388   926  3794 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 18:30:10.292   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:11.293   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 18:30:14.398  5549  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 18:30:14.399   926  3795 D WifiService: setWifiEnabled: true pid=5549, uid=10077
11-22 18:30:14.400   926  3795 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 18:30:14.409   508   918 D SoftapController: Softap fwReload - Ok
,11-22 18:30:14.414   508   918 D CommandListener: Setting iface cfg
11-22 18:30:14.415   508   918 D CommandListener: Trying to bring down wlan0
,11-22 18:30:14.416   508   918 D CommandListener: Clearing all IP addresses on wlan0
,11-22 18:30:14.421   926  2909 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 18:30:15.106   926  2909 D wifi    : set interface wlan0 flags (UP)
,11-22 18:30:15.113   926  2909 I WifiHAL : Initializing wifi
11-22 18:30:15.113   926  2909 I WifiHAL : Creating socket
11-22 18:30:15.113   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-22 18:30:15.121   926  2909 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-22 18:30:15.122   926  2909 D wifi    : Did set static halHandle = 0x7f68ff4100
,11-22 18:30:15.122   926  2909 D wifi    : halHandle = 0x7f68ff4100, mVM = 0x7f8368d140, mCls = 0x15ca
11-22 18:30:15.122   926  2909 D wifi    : array field set
11-22 18:30:15.123   926  2909 I WifiNative-HAL: interface[0] = wlan0
11-22 18:30:15.126   926  5902 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547222405376
11-22 18:30:15.126   926  5902 D wifi    : waitForHalEvents called, vm = 0x7f8368d140, obj = 0x15ca, env = 0x7f6b3cb100
,11-22 18:30:15.170  5903  5903 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 18:30:15.227   926  2909 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-22 18:30:15.234  5903  5903 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 18:30:15.315  5903  5903 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 18:30:15.315  5903  5903 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 18:30:15.341   926  2909 D WifiConfigStore: Loading config and enabling all networks 
,11-22 18:30:15.374   926  2909 D WifiConfigStore: loaded 0 passpoint configs
,11-22 18:30:15.375   926  2909 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-22 18:30:15.376   926  2909 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-22 18:30:15.377   926  2909 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-22 18:30:15.377   926  2909 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-22 18:30:15.378   926  2909 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-22 18:30:15.379   926  2909 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-22 18:30:15.380   926  2909 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-22 18:30:15.380   926  2909 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-22 18:30:15.380   926  2909 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-22 18:30:15.380   926  2909 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-22 18:30:15.380   926  2909 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-22 18:30:15.380   926  2909 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-22 18:30:15.383   926  2909 D WifiNative-HAL: Setting external_sim to 1
,11-22 18:30:15.383   926  2909 D wifi    : setting dfs flag to true, 0x7f6aaff180
11-22 18:30:15.383   926  2909 D WifiStateMachine: Setting OUI to DA-A1-19
11-22 18:30:15.383  4910  4910 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 18:30:15.384   926  2909 D wifi    : setting scan oui 0x7f6aaff180
11-22 18:30:15.384   926  2909 D WifiHAL : Sending mac address OUI
,11-22 18:30:15.388   926  2909 E native  : do suspend false
,11-22 18:30:15.397   926  2909 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-22 18:30:15.398   926   926 D RttService: SCAN_AVAILABLE : 3
11-22 18:30:15.398   508   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-22 18:30:15.399   926  3018 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 18:30:15.400   508   918 D CommandListener: Setting iface cfg
,11-22 18:30:15.405   926  2901 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
11-22 18:30:15.405   926  2901 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 18:30:15.418   926  2901 D WifiNative-HAL: p2pGetDeviceAddress
11-22 18:30:15.418   926  2901 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-22 18:30:15.425   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=248936 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=19 mControllerEnergyUsed=72 }
,11-22 18:30:18.481  5903  5903 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 18:30:18.491  5903  5903 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 18:30:18.497  5903  5903 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 18:30:18.522   926  2909 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-22 18:30:18.523   926  2909 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-22 18:30:18.524   926  2909 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 18:30:18.536   926  2909 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 18:30:18.574   926  2909 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 18:30:18.580  5903  5903 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 18:30:19.014  5903  5903 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-22 18:30:19.049  5903  5903 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-22 18:30:19.049  5903  5903 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 18:30:19.061   926  2909 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 18:30:19.061   926  2909 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 18:30:19.062   926  2911 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 18:30:19.079   926  2909 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 18:30:19.089   508   918 D CommandListener: Setting iface cfg
,11-22 18:30:19.094   926  2909 D WifiStateMachine: Start Dhcp Watchdog 3
,11-22 18:30:19.101   926  5908 D DhcpClient: Receive thread started
,11-22 18:30:19.106   926  2909 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-22 18:30:19.106   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-22 18:30:19.106   926  2911 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-22 18:30:19.196   926  2909 E native  : do suspend false
,11-22 18:30:19.216   926  5907 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 18:30:19.229   926  5908 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-22 18:30:19.230   926  5907 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-22 18:30:19.234   926  5907 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-22 18:30:19.257   926  5908 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 18:30:19.258   926  5907 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-22 18:30:19.263   508   918 D CommandListener: Setting iface cfg
,11-22 18:30:19.268   926  2909 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-22 18:30:19.273   926  5907 D DhcpClient: Scheduling renewal in 86399s
,11-22 18:30:19.291   926  2909 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-22 18:30:19.293   926  2909 D WifiConfigStore: No blacklist allowed without epno enabled
11-22 18:30:19.294   926  2911 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-22 18:30:19.297   926  2911 D ConnectivityService: Adding iface wlan0 to network 102
,11-22 18:30:19.301   926  2909 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-22 18:30:19.343   926  2911 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-22 18:30:19.343   926  2911 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-22 18:30:19.348   926  2911 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-22 18:30:19.350   926  2911 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
11-22 18:30:19.351   926  2911 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-22 18:30:19.359   926  2911 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:30:19.364   926  2911 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-22 18:30:19.364   926  2911 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-22 18:30:19.364   926  2911 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-22 18:30:19.364   926  2909 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-22 18:30:19.364   926  2911 D ConnectivityService:    accepting network in place of null
11-22 18:30:19.364   926  2909 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 18:30:19.365   926  2911 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 18:30:19.373   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=252884, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 18:30:19.387   508   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 18:30:19.411   508   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 18:30:19.415   926  2911 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-22 18:30:19.415   926  2911 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 18:30:19.416  3670  3815 W QCNEJ   : |CORE| network available: 102
11-22 18:30:19.417   926  2911 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-22 18:30:19.418   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-22 18:30:19.422  3670  3815 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-22 18:30:19.424  3670  3815 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-22 18:30:19.424  5549  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 18:30:19.424  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 18:30:19.424  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 18:30:19.424  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 18:30:19.424  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 18:30:19.424  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 18:30:19.424  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 18:30:19.424  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 18:30:19.424  5549  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 18:30:19.424  3670  3815 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-22 18:30:19.429  5549  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 18:30:19.429  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.429  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@488be2e removed from the list
11-22 18:30:19.429  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:30:19.433  5549  5598 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-22 18:30:19.433  5549  5598 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-22 18:30:19.435  4961  4982 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 18:30:19.435  4961  4982 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-22 18:30:19.435  4961  4982 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-22 18:30:19.435  4961  4982 E SarControlService: no key has been found,reset the power
11-22 18:30:19.435  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-22 18:30:19.436  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 18:30:19.436  5549  5598 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bd3572e Bundle[{}]
11-22 18:30:19.436  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 18:30:19.436  5549  5598 I io.jxcore.node.LifeCycleMonitor: start: OK
11-22 18:30:19.436  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 18:30:19.436  5549  5598 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-22 18:30:19.436  4986  4986 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 18:30:19.437  5549  5598 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-22 18:30:19.437  5549  5598 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-22 18:30:19.438  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 18:30:19.438  5549  5598 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-22 18:30:19.438  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-22 18:30:19.438  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 18:30:19.438  5549  5598 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-22 18:30:19.441   926  5905 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-22 18:30:19.439  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 18:30:19.446  3798  3798 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 18:30:19.448  5549  5598 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-22 18:30:19.449  5549  5598 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-22 18:30:19.449  5549  5598 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
11-22 18:30:19.449  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000f003000000000000ffffffff]
11-22 18:30:19.450  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 18:30:19.450  4986  5000 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-22 18:30:19.451  3798  3798 D SystemUpdateService: onCreate
11-22 18:30:19.451  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 18:30:19.451  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf2dcf added. We now have 3 listener(s)
11-22 18:30:19.452  3900  3900 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-22 18:30:19.452  4986  4986 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 18:30:19.453  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:30:19.453  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 18:30:19.453  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 18:30:19.453  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:30:19.453  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@775c35c added. We now have 4 listener(s)
11-22 18:30:19.453  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 18:30:19.453  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 18:30:19.454  4961  4971 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-22 18:30:19.454  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 18:30:19.456  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000f103000000000000ffffffff]
11-22 18:30:19.456  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 18:30:19.456  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 18:30:19.456  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d26665 added. We now have 4 listener(s)
11-22 18:30:19.456  4986  5000 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-22 18:30:19.457  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:30:19.457  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 18:30:19.457  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 18:30:19.457  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 18:30:19.457  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:30:19.457  4961  4972 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 18:30:19.457  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e68f3a added. We now have 5 listener(s)
11-22 18:30:19.458  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 18:30:19.458  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:30:19.458  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:30:19.458  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:30:19.458  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:30:19.458  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:30:19.458  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 18:30:19.458  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf2dcf removed from the list
11-22 18:30:19.458  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.458  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@775c35c removed from the list
11-22 18:30:19.458  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:30:19.458  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.458  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.459  3798  3798 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-22 18:30:19.459  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.460  5549  5598 D org.thaliproject.p2p.btconn,ectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.460  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.460  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:30:19.460  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:30:19.460  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.460  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@775c35c not in the list
11-22 18:30:19.460  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.460  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.461  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.461  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.461  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.461  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:30:19.461  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:30:19.461  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.461  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e68f3a removed from the list
11-22 18:30:19.461  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:30:19.461  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:30:19.461  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 18:30:19.461  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d26665 removed from the list
11-22 18:30:19.462  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 18:30:19.462  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@caad7eb added. We now have 3 listener(s)
11-22 18:30:19.463  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:30:19.463  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 18:30:19.463  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 18:30:19.463  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 18:30:19.463  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d49b948 added. We now have 4 listener(s)
11-22 18:30:19.463  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 18:30:19.465  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 18:30:19.467  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 18:30:19.467  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48803e1 added. We now have 4 listener(s)
,11-22 18:30:19.468  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:30:19.468  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 18:30:19.468  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 18:30:19.468  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:30:19.469  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6506 added. We now have 5 listener(s)
11-22 18:30:19.469  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 18:30:19.469  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 18:30:19.469  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-22 18:30:19.469  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 18:30:19.469  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 18:30:19.469  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 18:30:19.470  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 18:30:19.471  3798  3798 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-22 18:30:19.473  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 18:30:19.474  5549  5598 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-22 18:30:19.474  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 18:30:19.476  3798  5314 I iu.UploadsManager: num queued entries: 0
11-22 18:30:19.476  3798  5314 I iu.UploadsManager: num updated entries: 0
11-22 18:30:19.477  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.477  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 18:30:19.477  3798  5314 I iu.SyncManager: NEXT; no task
11-22 18:30:19.477  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-22 18:30:19.478  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 18:30:19.478  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 18:30:19.480  3798  5918 I SystemUpdateService: active receiver: enabled
,11-22 18:30:19.482  3798  3798 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-22 18:30:19.483  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.483  3798  3798 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-22 18:30:19.483  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-22 18:30:19.483  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 18:30:19.483  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 18:30:19.483  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 18:30:19.484  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.484  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:30:19.485  5684  5684 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 18:30:19.487  5849  5888 D BtGatt.GattService: registerClient() - UUID=0d7b0d68-8cd2-4215-bb35-1139c2c37071
11-22 18:30:19.488  5849  5865 D BtGatt.GattService: onClientRegistered() - UUID=0d7b0d68-8cd2-4215-bb35-1139c2c37071, clientIf=5
,11-22 18:30:19.488  5549  5594 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 18:30:19.489  5849  5859 D BtGatt.GattService: start scan with filters
,11-22 18:30:19.491  5684  5684 D SprintDMHelper: simOperator: 
11-22 18:30:19.491  5684  5684 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 18:30:19.494  5849  5868 D BtGatt.ScanManager: handling starting scan
11-22 18:30:19.494  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 18:30:19.494  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.494  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 18:30:19.494  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.494  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 18:30:19.494  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 18:30:19.495  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.495  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 18:30:19.495  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 18:30:19.495  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.495  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.495  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.495  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-22 18:30:19.495  5849  5868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 18:30:19.496  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 18:30:19.496  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 18:30:19.499  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.499  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:30:19.499  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.499  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.499  5549  5598 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 18:30:19.499  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 18:30:19.499  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 18:30:19.499  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 18:30:19.500  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:30:19.500  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:30:19.500  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 18:30:19.500  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-22 18:30:19.500  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.500  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 18:30:19.500  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 18:30:19.500  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.500  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.500  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.500  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 18:30:19.500  5849  5865 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 18:30:19.500  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.501  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.501  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:30:19.501  5849  5868 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 18:30:19.502  5849  5860 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 18:30:19.502  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-22 18:30:19.503  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:30:19.503  5849  5859 D BtGatt.GattService: stopScan() - queue size =1
11-22 18:30:19.504  5849  5887 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 18:30:19.505  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 18:30:19.505  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.505  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 18:30:19.505  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.505  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.506  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.506  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.506  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 18:30:19.506  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.506  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.506  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.506  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 18:30:19.506  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 18:30:19.507  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 18:30:19.507  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.508  5849  5865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 18:30:19.508  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.508  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.508  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:30:19.509  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.509  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.509  5849  5868 D BtGatt.ScanManager: Starting BLE batch scan
11-22 18:30:19.509  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.509  5849  5868 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 18:30:19.512  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.512  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.512  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.513  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:30:19.513  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:30:19.513  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:30:19.513  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:30:19.513  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:30:19.513  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:30:19.513  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:30:19.513  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:30:19.513  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 18:30:19.513  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@caad7eb removed from the list
11-22 18:30:19.513  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.513  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d49b948 removed from the list
11-22 18:30:19.513  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:30:19.513  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.513  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.514   926  5905 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 17:30:19 GMT], X-Android-Received-Millis=[1479835819513], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479835819471]}
11-22 18:30:19.514  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 18:30:19.514  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.514  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 18:30:19.514  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 18:30:19.514  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.514  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.515  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.515  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:30:19.515   926  2911 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 18:30:19.515  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.515  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.515   926  2911 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-22 18:30:19.516   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-22 18:30:19.516  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.517  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.517  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.517  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.517  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.517  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.517  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:30:19.517   926  2911 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-22 18:30:19.517  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 18:30:19.517  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.517  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d49b948 not in the list
11-22 18:30:19.517  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.517  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.519  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.519  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.519  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.519  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:30:19.519  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:30:19.519  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.519  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6506 removed from the list
11-22 18:30:19.519  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:30:19.519  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:30:19.520  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 18:30:19.520  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48803e1 removed from the list
11-22 18:30:19.520  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 18:30:19.520  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c185963 added. We now have 3 listener(s)
11-22 18:30:19.521  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:30:19.522  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 18:30:19.522  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 18:30:19.522  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:30:19.522  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72c6960 added. We now have 4 listener(s)
11-22 18:30:19.522  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 18:30:19.522  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 18:30:19.523  3798  5918 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-22 18:30:19.523  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 18:30:19.523  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6444e19 added. We now have 4 listener(s)
11-22 18:30:19.524  5849  5865 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 18:30:19.524  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.524  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:30:19.525  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 18:30:19.525  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 18:30:19.525  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:30:19.525  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b370ede added. We now have 5 listener(s)
11-22 18:30:19.525  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 18:30:19.525  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 18:30:19.526  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 18:30:19.526  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 18:30:19.526  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 18:30:19.526  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 18:30:19.526  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 18:30:19.528  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 18:30:19.530  5849  5865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 18:30:19.531  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.531  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 18:30:19.531  5549  5598 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 18:30:19.531  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 18:30:19.534  5849  5868 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 18:30:19.535  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.535  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 18:30:19.536  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 18:30:19.536  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 18:30:19.536  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 18:30:19.537  3798  5918 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-22 18:30:19.537  3798  5918 I SystemUpdateService: now status is 0 (complete)
11-22 18:30:19.537  3798  5918 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 18:30:19.537  3798  5918 I SystemUpdateService: file has been verified
11-22 18:30:19.537  3798  5918 I SystemUpdateService: OTA package size = 21989297
11-22 18:30:19.540  5849  5865 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 18:30:19.540  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.540  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 18:30:19.540  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.540  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 18:30:19.540  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 18:30:19.540  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 18:30:19.540  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.540  5849  5865 E BtGatt.ContextMap: Context not found for ID 5
11-22 18:30:19.542  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:30:19.546  5849  5859 D BtGatt.GattService: registerClient() - UUID=6f65a929-d270-46f2-bf3e-9a1796971742
11-22 18:30:19.547  5849  5865 D BtGatt.GattService: onClientRegistered() - UUID=6f65a929-d270-46f2-bf3e-9a1796971742, clientIf=5
11-22 18:30:19.547  5849  5865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 18:30:19.547  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.547  5549  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 18:30:19.548  5849  5860 D BtGatt.GattService: start scan with filters
11-22 18:30:19.548  5849  5868 D BtGatt.ScanManager: stopping BLe Batch
11-22 18:30:19.550  3798  5918 I SystemUpdateService: showing system update notification
11-22 18:30:19.551  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 18:30:19.551  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.551  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 18:30:19.551  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.551  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 18:30:19.551  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 18:30:19.551  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.551  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 18:30:19.551  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 18:30:19.551  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.551  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.552  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.552  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.552  5849  5865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 18:30:19.552  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.552  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 18:30:19.553  5849  5868 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 18:30:19.553  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.557  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.557  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:30:19.557  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.557  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.557  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 18:30:19.557  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.557  5549  5598 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-22 18:30:19.557  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:30:19.557  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:30:19.557  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:30:19.557  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:30:19.558  5849  5865 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 18:30:19.558  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.558  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 18:30:19.558  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:30:19.558  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:30:19.558  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 18:30:19.558  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c185963 removed from the list
11-22 18:30:19.558  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.558  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72c6960 removed from the list
11-22 18:30:19.558  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:30:19.558  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 18:30:19.558  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:30:19.558  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.558  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-22 18:30:19.558  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 18:30:19.558  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 18:30:19.558  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:30:19.559  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.560  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.560  5849  5868 D BtGatt.ScanManager: handling starting scan
11-22 18:30:19.560  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.560  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.560  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:30:19.560  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.560  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.560  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.560  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:30:19.561  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:30:19.561  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.561  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72c6960 not in the list
11-22 18:30:19.561  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 18:30:19.561  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.561  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 18:30:19.561  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 18:30:19.561  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.561  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.561  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.561  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 18:30:19.561  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.561   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-22 18:30:19.563  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:30:19.563  5849  5860 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 18:30:19.563  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 18:30:19.564  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:30:19.564  5849  5888 D BtGatt.GattService: stopScan() - queue size =1
11-22 18:30:19.564  3798  3798 D SystemUpdateService: onDestroy
,11-22 18:30:19.565  5849  5886 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 18:30:19.565  5849  5865 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 18:30:19.565  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 18:30:19.565  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.565  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.565  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 18:30:19.565  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.565  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.565  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.566  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.566  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 18:30:19.566  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.566  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.566  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.566  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 18:30:19.566  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 18:30:19.566  5849  5868 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 18:30:19.566  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 18:30:19.567  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.568  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.568  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:30:19.568  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.568  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.568  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:30:19.568  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:30:19.568  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.569  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b370ede removed from the list
11-22 18:30:19.569  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:30:19.569  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:30:19.569  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 18:30:19.569  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:30:19.569  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6444e19 removed from the list
11-22 18:30:19.569  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:30:19.569  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 18:30:19.569  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.570  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 18:30:19.570  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 18:30:19.570  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.570  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.570  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.570  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:30:19.570  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 18:30:19.570  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.570  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.570  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99591db added. We now have 3 listener(s)
11-22 18:30:19.571  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.571  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.571  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.571  5849  5865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 18:30:19.571  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.571  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:30:19.572  5849  5868 D BtGatt.ScanManager: Starting BLE batch scan
11-22 18:30:19.572  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 18:30:19.572  5849  5868 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 18:30:19.572  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 18:30:19.572  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:30:19.572  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1820478 added. We now have 4 listener(s)
11-22 18:30:19.572  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 18:30:19.573  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 18:30:19.574  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 18:30:19.574  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e88a751 added. We now have 4 listener(s)
11-22 18:30:19.575  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:30:19.575  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 18:30:19.576  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 18:30:19.576  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:30:19.576  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd01bb6 added. We now have 5 listener(s)
11-22 18:30:19.576  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 18:30:19.576  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 18:30:19.576  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 18:30:19.576  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 18:30:19.576  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 18:30:19.576  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 18:30:19.579  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 18:30:19.581  5849  5865 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 18:30:19.581  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.581  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 18:30:19.581  5549  5598 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 18:30:19.582  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 18:30:19.585  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.585  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 18:30:19.587  5849  5865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 18:30:19.587  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.587  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 18:30:19.587  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 18:30:19.587  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 18:30:19.589  5849  5868 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 18:30:19.592  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.592  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 18:30:19.592  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 18:30:19.592  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 18:30:19.592  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 18:30:19.592  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.594  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:30:19.594  5849  5865 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 18:30:19.594  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.594  5849  5865 E BtGatt.ContextMap: Context not found for ID 5
11-22 18:30:19.596  5849  5886 D BtGatt.GattService: registerClient() - UUID=4b046c17-ed3d-4946-aa40-032ce2b2bff6
11-22 18:30:19.596  5849  5865 D BtGatt.GattService: onClientRegistered() - UUID=4b046c17-ed3d-4946-aa40-032ce2b2bff6, clientIf=5
11-22 18:30:19.597  5549  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 18:30:19.597  5849  5887 D BtGatt.GattService: start scan with filters
11-22 18:30:19.599  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 18:30:19.600  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.600  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 18:30:19.600  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.600  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 18:30:19.600  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 18:30:19.600  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.600  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 18:30:19.600  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 18:30:19.600  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.600  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.600  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.600  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.601  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 18:30:19.601  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.601  5849  5865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 18:30:19.601  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.601  5849  5868 D BtGatt.ScanManager: stopping BLe Batch
11-22 18:30:19.603  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.603  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:30:19.603  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.603  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.604  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.605  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:30:19.605  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:30:19.605  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:30:19.605  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:30:19.605  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 18:30:19.605  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:30:19.606  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:30:19.606  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 18:30:19.606  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99591db removed from the list
11-22 18:30:19.606  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.606  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1820478 removed from the list
11-22 18:30:19.606  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:30:19.606  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 18:30:19.606  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:30:19.606  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.606  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-22 18:30:19.606  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 18:30:19.606  5549  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 18:30:19.606  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 18:30:19.606  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.606  5849  5865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 18:30:19.606  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.606  5849  5868 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 18:30:19.607  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.607  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.607  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.607  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 18:30:19.607  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.607  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.607  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.607  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:30:19.607  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:30:19.607  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.607  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1820478 not in the list
11-22 18:30:19.607  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 18:30:19.607  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.607  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 18:30:19.607  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 18:30:19.608  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.608  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.608  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.608  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 18:30:19.608  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.609  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:30:19.609  5849  5860 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 18:30:19.609  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 18:30:19.610  5549  5598 D BluetoothAdapter: STATE_ON
11-22 18:30:19.610  5849  5887 D BtGatt.GattService: stopScan() - queue size =0
11-22 18:30:19.611  5849  5859 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 18:30:19.611  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 18:30:19.611  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.611  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 18:30:19.611  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.611  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.611  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.611  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.611  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 18:30:19.611  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.612  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.612  5849  5865 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 18:30:19.612  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.612  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.612  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 18:30:19.612  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 18:30:19.612  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 18:30:19.613  5849  5868 D BtGatt.ScanManager: handling starting scan
11-22 18:30:19.614  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.615  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.615  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:30:19.615  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.615  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.615  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:30:19.615  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:30:19.615  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.616  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd01bb6 removed from the list
11-22 18:30:19.616  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:30:19.616  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:30:19.616  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:30:19.616  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 18:30:19.616  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 18:30:19.616  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e88a751 removed from the list
11-22 18:30:19.616  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 18:30:19.616  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.616  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 18:30:19.616  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 18:30:19.616  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.616  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.616  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.616  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 18:30:19.616  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 18:30:19.616  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.616  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2826153 added. We now have 3 listener(s)
11-22 18:30:19.616  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.617  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.617  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:30:19.617  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.617  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 18:30:19.617  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 18:30:19.617  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 18:30:19.618  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:30:19.618  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45cea90 added. We now have 4 listener(s)
11-22 18:30:19.618  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 18:30:19.618  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 18:30:19.619  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 18:30:19.619  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@667ef89 added. We now have 4 listener(s)
11-22 18:30:19.619  5849  5865 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 18:30:19.619  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.620  5849  5868 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 18:30:19.620  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 18:30:19.621  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 18:30:19.621  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 18:30:19.621  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 18:30:19.621  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232eb8e added. We now have 5 listener(s)
11-22 18:30:19.621  5549  5598 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 18:30:19.621  5549  5598 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 18:30:19.621  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:30:19.621  5549  5598 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 18:30:19.621  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:30:19.622  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:30:19.622  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 18:30:19.622  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2826153 removed from the list
11-22 18:30:19.622  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.622  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45cea90 removed from the list
11-22 18:30:19.622  5549  5598 D io.jxcore.node.ConnectivityMonitor: stop
11-22 18:30:19.622  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.622  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.623  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.623  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.623  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.623  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:30:19.624  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:30:19.624  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.624  5549  5598 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45cea90 not in the list
11-22 18:30:19.624  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.624  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.625  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.625  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.625  5549  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 18:30:19.625  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 18:30:19.625  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 18:30:19.625  5549  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 18:30:19.625  5549  5598 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232eb8e removed from the list
11-22 18:30:19.625  5549  5598 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 18:30:19.625  5549  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 18:30:19.625  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 18:30:19.626  5549  5598 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@667ef89 removed from the list
11-22 18:30:19.626  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-22 18:30:19.626  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-22 18:30:19.626  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-22 18:30:19.627  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 18:30:19.627  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-22 18:30:19.627  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 18:30:19.627  5849  5865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 18:30:19.627  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.627  5849  5868 D BtGatt.ScanManager: Starting BLE batch scan
11-22 18:30:19.627  5849  5868 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 18:30:19.636  5849  5865 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 18:30:19.636  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.641  5849  5865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 18:30:19.641  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.643  5849  5868 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 18:30:19.647  5849  5865 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 18:30:19.647  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.647  5849  5865 E BtGatt.ContextMap: Context not found for ID 5
11-22 18:30:19.653  5849  5865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 18:30:19.653  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.654  5849  5868 D BtGatt.ScanManager: stopping BLe Batch
,11-22 18:30:19.659  5849  5865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 18:30:19.659  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 18:30:19.659  5849  5868 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 18:30:19.661  4910  5922 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-22 18:30:19.664  5849  5865 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 18:30:19.664  5849  5865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 18:30:20.017  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 18:30:20.071  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 18:30:20.117  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 18:30:21.294   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:21.755  5549  5930 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 18:30:21.755  5549  5930 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 18:30:22.123   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:30:22.295   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:22.556  5549  5930 W !!      : call onHalfStreamCopied
,11-22 18:30:22.556  5549  5930 I testCopyDataAndClose: closing input stream
,11-22 18:30:23.296   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:23.322  5549  5930 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 18:30:23.322  5549  5930 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 18:30:23.322  5549  5930 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 18:30:23.322  5549  5930 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 18:30:23.322  5549  5930 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 18:30:23.322  5549  5930 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 18:30:23.322  5549  5930 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 18:30:23.322  5549  5930 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 18:30:23.322  5549  5930 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 18:30:23.322  5549  5930 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 18:30:23.322  5549  5930 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 18:30:24.297   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:25.145   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:30:25.297   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:26.298   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 18:30:27.367   926  2911 D ConnectivityService: handlePromptUnvalidated 102
,11-22 18:30:27.537  5549  5931 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 18:30:27.537  5549  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 18:30:28.167   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:30:29.537  5549  5598 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-22 18:30:29.537  5549  5598 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 18:30:29.537  5549  5598 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-22 18:30:29.695  5549  5932 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 18:30:29.695  5549  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 18:30:29.708  5549  5931 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
11-22 18:30:29.708  5549  5931 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 18:30:29.708  5549  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-22 18:30:30.419   926  2909 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,11-22 18:30:31.322  5549  5932 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 18:30:31.322  5549  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 18:30:31.322  5549  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 18:30:31.322  5549  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 18:30:31.323  5549  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 18:30:31.323  5549  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 18:30:31.323  5549  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 18:30:31.323  5549  5932 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 18:30:31.323  5549  5932 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-22 18:30:31.323  5549  5932 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 18:30:31.323  5549  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 18:30:35.524  5549  5933 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 18:30:35.524  5549  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 18:30:35.525  5549  5933 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-22 18:30:35.525  5549  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 18:30:35.525  5549  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 18:30:35.525  5549  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 18:30:35.525  5549  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 18:30:35.525  5549  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 18:30:35.525  5549  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 18:30:35.525  5549  5933 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 18:30:35.526  5549  5933 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 18:30:35.526  5549  5933 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 18:30:35.526  5549  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-22 18:30:35.527  5549  5598 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-22 18:30:35.531  5549  5934 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 18:30:35.531  5549  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 18:30:35.532  5549  5934 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-22 18:30:35.532  5549  5934 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 18:30:35.532  5549  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-22 18:30:35.532  5549  5934 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-22 18:30:35.533  5549  5934 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 18:30:35.533  5549  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-22 18:30:35.538  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-22 18:30:35.538  5549  5598 I jxcore-log: 
,11-22 18:30:35.538  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-22 18:30:35.538  5549  5598 I jxcore-log: 
11-22 18:30:35.538  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-22 18:30:35.538  5549  5598 I jxcore-log: 
11-22 18:30:35.539  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-22 18:30:35.539  5549  5598 I jxcore-log: 
11-22 18:30:35.539  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG UnitTest_app: 'Total duration:  91669'
11-22 18:30:35.539  5549  5598 I jxcore-log: 
,11-22 18:30:35.541  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-22 18:30:35.541  5549  5598 I jxcore-log: 
,11-22 18:30:35.544  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 18:30:35.544  5549  5598 I jxcore-log: 
,11-22 18:30:35.545  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 18:30:35.545  5549  5598 I jxcore-log: 
11-22 18:30:35.546  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 18:30:35.546  5549  5598 I jxcore-log: 
11-22 18:30:35.546  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 18:30:35.546  5549  5598 I jxcore-log: 
11-22 18:30:35.546  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 18:30:35.546  5549  5598 I jxcore-log: 
,11-22 18:30:35.546  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 18:30:35.546  5549  5598 I jxcore-log: 
11-22 18:30:35.547  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 18:30:35.547  5549  5598 I jxcore-log: 
11-22 18:30:35.547  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 18:30:35.547  5549  5598 I jxcore-log: 
11-22 18:30:35.547  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 18:30:35.547  5549  5598 I jxcore-log: 
11-22 18:30:35.548  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 18:30:35.548  5549  5598 I jxcore-log: 
11-22 18:30:35.548  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 18:30:35.548  5549  5598 I jxcore-log: 
11-22 18:30:35.548  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 18:30:35.548  5549  5598 I jxcore-log: 
11-22 18:30:35.548  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 18:30:35.548  5549  5598 I jxcore-log: 
,11-22 18:30:35.548  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 18:30:35.548  5549  5598 I jxcore-log: 
11-22 18:30:35.549  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 18:30:35.549  5549  5598 I jxcore-log: 
11-22 18:30:35.549  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 18:30:35.549  5549  5598 I jxcore-log: 
11-22 18:30:35.549  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","ssidName":"<unknown ssid>"}'
11-22 18:30:35.549  5549  5598 I jxcore-log: 
11-22 18:30:35.549  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 18:30:35.549  5549  5598 I jxcore-log: 
11-22 18:30:35.550  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 18:30:35.550  5549  5598 I jxcore-log: 
11-22 18:30:35.550  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 18:30:35.550  5549  5598 I jxcore-log: 
11-22 18:30:35.550  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 18:30:35.550  5549  5598 I jxcore-log: 
11-22 18:30:35.551  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 18:30:35.551  5549  5598 I jxcore-log: 
11-22 18:30:35.551  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 18:30:35.551  5549  5598 I jxcore-log: 
11-22 18:30:35.551  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 18:30:35.551  5549  5598 I jxcore-log: 
,11-22 18:30:35.554  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 18:30:35.554  5549  5598 I jxcore-log: 
,11-22 18:30:35.554  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 18:30:35.554  5549  5598 I jxcore-log: 
11-22 18:30:35.555  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 18:30:35.555  5549  5598 I jxcore-log: 
11-22 18:30:35.555  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 18:30:35.555  5549  5598 I jxcore-log: 
11-22 18:30:35.555  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 18:30:35.555  5549  5598 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-22 18:30:35.555  5549  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 18:30:35.555  5549  5598 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-22 18:30:35.556  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 18:30:35.556  5549  5598 I jxcore-log: 
11-22 18:30:35.556  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 18:30:35.556  5549  5598 I jxcore-log: 
11-22 18:30:35.556  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 18:30:35.556  5549  5598 I jxcore-log: 
11-22 18:30:35.556  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 18:30:35.556  5549  5598 I jxcore-log: 
11-22 18:30:35.556  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 18:30:35.556  5549  5598 I jxcore-log: 
,11-22 18:30:35.557  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 18:30:35.557  5549  5598 I jxcore-log: 
,11-22 18:30:35.562  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-22 18:30:35.562  5549  5598 I jxcore-log: 
,11-22 18:30:35.562  5549  5598 I jxcore-log: 2016-11-22 17:30:35 - WARN testUtils: 'myNameCallback not set!'
11-22 18:30:35.562  5549  5598 I jxcore-log: 
,11-22 18:30:35.569  5549  5549 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-22 18:30:37.637  5549  5598 I jxcore-log: 2016-11-22 17:30:37 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-22 18:30:37.637  5549  5598 I jxcore-log: 
,11-22 18:30:37.639  5549  5598 I jxcore-log: 2016-11-22 17:30:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-22 18:30:37.639  5549  5598 I jxcore-log: 
,11-22 18:30:37.988  5549  5598 I jxcore-log: 2016-11-22 17:30:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-22 18:30:37.988  5549  5598 I jxcore-log: 
,11-22 18:30:37.999  5549  5598 I jxcore-log: 2016-11-22 17:30:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-22 18:30:37.999  5549  5598 I jxcore-log: 
,11-22 18:30:39.124  5549  5598 I jxcore-log: 2016-11-22 17:30:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-22 18:30:39.124  5549  5598 I jxcore-log: 
,11-22 18:30:39.319  5549  5598 I jxcore-log: 2016-11-22 17:30:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-22 18:30:39.319  5549  5598 I jxcore-log: 
,11-22 18:30:39.324  5549  5598 I jxcore-log: 2016-11-22 17:30:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-22 18:30:39.324  5549  5598 I jxcore-log: 
,11-22 18:30:39.329  5549  5598 I jxcore-log: 2016-11-22 17:30:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-22 18:30:39.329  5549  5598 I jxcore-log: 
,11-22 18:30:39.819  5549  5598 I jxcore-log: 2016-11-22 17:30:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-22 18:30:39.819  5549  5598 I jxcore-log: 
,11-22 18:30:39.864  5549  5598 I jxcore-log: 2016-11-22 17:30:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-22 18:30:39.864  5549  5598 I jxcore-log: 
,11-22 18:30:39.877  5549  5598 I jxcore-log: 2016-11-22 17:30:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-22 18:30:39.877  5549  5598 I jxcore-log: 
,11-22 18:30:39.881  5549  5598 I jxcore-log: 2016-11-22 17:30:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-22 18:30:39.881  5549  5598 I jxcore-log: 
,11-22 18:30:40.152  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-22 18:30:40.152  5549  5598 I jxcore-log: 
,11-22 18:30:40.282  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-22 18:30:40.282  5549  5598 I jxcore-log: 
,11-22 18:30:40.655  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-22 18:30:40.655  5549  5598 I jxcore-log: 
,11-22 18:30:40.663  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-22 18:30:40.663  5549  5598 I jxcore-log: 
,11-22 18:30:40.667  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-22 18:30:40.667  5549  5598 I jxcore-log: 
,11-22 18:30:40.673  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-22 18:30:40.673  5549  5598 I jxcore-log: 
,11-22 18:30:40.678  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-22 18:30:40.678  5549  5598 I jxcore-log: 
,11-22 18:30:40.706  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-22 18:30:40.706  5549  5598 I jxcore-log: 
,11-22 18:30:40.741  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-22 18:30:40.741  5549  5598 I jxcore-log: 
,11-22 18:30:40.749  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-22 18:30:40.749  5549  5598 I jxcore-log: 
,11-22 18:30:40.755  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-22 18:30:40.755  5549  5598 I jxcore-log: 
,11-22 18:30:40.771  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-22 18:30:40.771  5549  5598 I jxcore-log: 
,11-22 18:30:40.787  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-22 18:30:40.787  5549  5598 I jxcore-log: 
,11-22 18:30:40.793  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-22 18:30:40.793  5549  5598 I jxcore-log: 
,11-22 18:30:40.798  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-22 18:30:40.798  5549  5598 I jxcore-log: 
,11-22 18:30:40.811  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-22 18:30:40.811  5549  5598 I jxcore-log: 
,11-22 18:30:40.829  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-22 18:30:40.829  5549  5598 I jxcore-log: 
,11-22 18:30:40.843  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-22 18:30:40.843  5549  5598 I jxcore-log: 
,11-22 18:30:40.854  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-22 18:30:40.854  5549  5598 I jxcore-log: 
,11-22 18:30:40.867  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-22 18:30:40.867  5549  5598 I jxcore-log: 
,11-22 18:30:40.877  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-22 18:30:40.877  5549  5598 I jxcore-log: 
,11-22 18:30:40.890  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-22 18:30:40.890  5549  5598 I jxcore-log: 
,11-22 18:30:40.900  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-22 18:30:40.900  5549  5598 I jxcore-log: 
,11-22 18:30:40.907  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-22 18:30:40.907  5549  5598 I jxcore-log: 
,11-22 18:30:40.929  5549  5598 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-22 18:30:40.930  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO testUtils: 'BLE multiple advertisement supported'
11-22 18:30:40.930  5549  5598 I jxcore-log: 
,11-22 18:30:40.964  5549  5598 I jxcore-log: 2016-11-22 17:30:40 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-22 18:30:40.964  5549  5598 I jxcore-log: 
,11-22 18:30:41.202  5549  5598 I jxcore-log: 2016-11-22 17:30:41 - DEBUG CoordinatedClient: 'connected to the test server'
11-22 18:30:41.202  5549  5598 I jxcore-log: 
,11-22 18:30:41.299   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:42.300   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:43.301   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:44.303   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:45.304   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:30:46.304   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 18:30:52.341   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:30:58.408   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:30:59.346   926  2909 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 18:31:05.153   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=298664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 18:31:06.306   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:31:07.307   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:31:08.309   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:31:09.310   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:31:10.312   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:31:11.206   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=304717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 18:31:11.313   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 18:31:30.326   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=323837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 18:31:36.233   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=329743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 18:31:36.313   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 18:31:36.314   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 18:31:37.741   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:31:39.349   926  2909 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 18:31:40.771   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:31:51.315   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:31:52.317   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:31:53.318   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:31:54.319   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:31:55.321   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:31:55.340   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=348850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 18:31:56.321   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 18:31:59.350   926  2909 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 18:32:01.260   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=354770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 18:32:01.323   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:01.961   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:32:02.324   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:03.325   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:04.327   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:04.993   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:32:05.328   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:06.329   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 18:32:16.330   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:17.331   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:18.332   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:19.333   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:20.334   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:20.406   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=373917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 18:32:21.335   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 18:32:23.100  5903  5903 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 18:32:26.353   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=379864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-22 18:32:29.250   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:32:32.272   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:32:36.336   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:37.338   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:38.339   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:39.340   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:39.355   926  2909 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 18:32:40.341   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:32:41.342   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 18:32:44.398   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:32:50.444   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:32:59.359   926  2909 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 18:33:01.343   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:33:02.345   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:33:03.346   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:33:04.347   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:33:05.349   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:33:05.556   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:33:06.350   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 18:33:08.590   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:33:10.486   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=423997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 18:33:16.393   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=429904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 18:33:17.669   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:33:19.362   926  2909 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 18:33:23.737   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:33:31.350   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 18:33:31.351   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 18:33:32.827   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:33:35.500   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=449010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 18:33:38.883   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:33:41.433   926  5906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=454943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 18:33:51.352   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:33:52.353   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:33:53.354   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:33:54.030   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:33:54.356   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:33:55.357   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 18:33:56.358   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 18:33:56.379  5549  5598 I jxcore-log: 2016-11-22 17:33:56 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-22 18:33:56.379  5549  5598 I jxcore-log: 
,11-22 18:33:56.710  5549  5598 I jxcore-log: 2016-11-22 17:33:56 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 18:33:56.710  5549  5598 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 18:33:56.710  5549  5598 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 18:33:56.710  5549  5598 I jxcore-log: emit@events.js:82:1
11-22 18:33:56.710  5549  5598 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 18:33:56.710  5549  5598 I jxcore-log: emit@events.js:82:1''
11-22 18:33:56.710  5549  5598 I jxcore-log: 
,11-22 18:33:56.711  5549  5598 I jxcore-log: 2016-11-22 17:33:56 - DEBUG CoordinatedClient: 'test client failed'
11-22 18:33:56.711  5549  5598 I jxcore-log: 
,11-22 18:33:56.721  5549  5598 I jxcore-log: 2016-11-22 17:33:56 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 18:33:56.721  5549  5598 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 18:33:56.721  5549  5598 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 18:33:56.721  5549  5598 I jxcore-log: emit@events.js:82:1
11-22 18:33:56.721  5549  5598 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 18:33:56.721  5549  5598 I jxcore-log: emit@events.js:82:1''
11-22 18:33:56.721  5549  5598 I jxcore-log: 
,11-22 18:33:56.723  5549  5598 I jxcore-log: 2016-11-22 17:33:56 - DEBUG CoordinatedClient: 'test client failed'
11-22 18:33:56.723  5549  5598 I jxcore-log: 
,11-22 18:33:56.727  5549  5598 I jxcore-log: 2016-11-22 17:33:56 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 18:33:56.727  5549  5598 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 18:33:56.727  5549  5598 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 18:33:56.727  5549  5598 I jxcore-log: emit@events.js:82:1
11-22 18:33:56.727  5549  5598 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 18:33:56.727  5549  5598 I jxcore-log: emit@events.js:82:1''
11-22 18:33:56.727  5549  5598 I jxcore-log: 
,11-22 18:33:56.729  5549  5598 I jxcore-log: 2016-11-22 17:33:56 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-22 18:33:56.729  5549  5598 I jxcore-log: 
,11-22 18:33:57.046   926  2911 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 18:33:57.331  5947  5947 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-22 18:33:57.336  5947  5947 D AndroidRuntime: CheckJNI is OFF
,11-22 18:33:57.363  5947  5947 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-22 18:33:57.391  5947  5947 I Radio-JNI: register_android_hardware_Radio DONE
,11-22 18:33:57.406  5947  5947 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-22 18:33:57.415   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-22 18:33:57.416   926   939 I ActivityManager: Killing 5549:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-22 18:33:57.527   926  3745 D GraphicsStats: Buffer count: 2
11-22 18:33:57.527   926  3132 I WindowState: WIN DEATH: Window{7202fa3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-22 18:33:57.527   926  2910 D WifiService: Client connection lost with reason: 4
,11-22 18:33:57.540   926   939 W ActivityManager: Force removing ActivityRecord{c1bd828 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-22 18:33:57.546   926   949 I art     : Starting a blocking GC Explicit
,11-22 18:33:57.555   926  2871 W ActivityManager: Spurious death for ProcessRecord{223351c 0:com.test.thalitest/u0a77}, curProc for 5549: null
,11-22 18:33:57.580  3358  3358 W Binder_6: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28004]" dev="sockfs" ino=28004 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 18:33:57.580  3358  3358 W Binder_6: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[28004]" dev="sockfs" ino=28004 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 18:33:57.583   926  3358 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5549 uid 10077
11-22 18:33:57.586  3589  3589 I Keyboard.Facilitator: onFinishInput()
,11-22 18:33:57.611  3900  3900 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,11-22 18:33:57.650   926   949 I art     : Explicit concurrent mark sweep GC freed 117726(8MB) AllocSpace objects, 69(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.813ms total 103.344ms
,11-22 18:33:57.657  3900  5961 I MicroRecognitionRnrImpl: Starting detection.
,11-22 18:33:57.658  3900  5962 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@400bd82
,11-22 18:33:57.660   513  5964 I AudioFlinger: AudioFlinger's thread 0xf22c0000 ready to run
,11-22 18:33:57.664   513  2931 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-22 18:33:57.669   926   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
11-22 18:33:57.670  3900  5962 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@400bd82
11-22 18:33:57.672  5947  5947 I art     : System.exit called, status: 0
11-22 18:33:57.672  5947  5947 I AndroidRuntime: VM exiting with result code 0.
,11-22 18:33:57.680   513  5964 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-22 18:33:57.680   513  5964 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-22 18:33:57.680   513  5964 I ACDB-LOADER: ACDB AFE returned = -19
11-22 18:33:57.680   513  5964 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-22 18:33:57.680   513  5964 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-22 18:33:57.680   513  5964 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-22 18:33:57.688   513  5964 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-22 18:33:57.692   926   949 I ActivityManager: Start proc 5968:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-22 18:33:57.692   926   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-22 18:33:57.703  3589  3589 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-22 18:33:57.708  5849  5849 D BluetoothMapAppObserver: onReceive
11-22 18:33:57.708  5849  5849 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-22 18:33:57.709  4005  4120 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-22 18:33:57.718   926  2873 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-22 18:33:57.725  3589  5980 I Keyboard.Facilitator.DecoderInitializer: run()
,11-22 18:33:57.732  3589  5980 I Decoder : createOrResetDecoder
,11-22 18:33:57.746  3340  5984 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-22 18:33:57.780   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-22 18:33:57.781  3900  3900 I HotwordWorkerImpl: onReady
,11-22 18:33:57.783    28    28 W kworker/3:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 18:33:57.783  3521  3521 I ConfigService: onCreate
,11-22 18:33:57.788  3712  3712 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
11-22 18:33:57.787    28    28 W kworker/3:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 18:33:57.799   926   938 E PackageManager: Failed to write settings, restoring backup
11-22 18:33:57.799   926   938 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
11-22 18:33:57.799   926   938 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-22 18:33:57.799   926   938 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-22 18:33:57.799   926   938 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
11-22 18:33:57.799   926   938 E PackageManager: 	at java.io.OutputStreamWriter.flush(OutputStreamWriter.java:161)
11-22 18:33:57.799   926   938 E PackageManager: 	at java.io.BufferedWriter.flush(BufferedWriter.java:124)
11-22 18:33:57.799   926   938 E PackageManager: 	at org.kxml2.io.KXmlSerializer.flush(KXmlSerializer.java:477)
11-22 18:33:57.799   926   938 E PackageManager: 	at org.kxml2.io.KXmlSerializer.endDocument(KXmlSerializer.java:169)
11-22 18:33:57.799   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4650)
11-22 18:33:57.799   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-22 18:33:57.799   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-22 18:33:57.799   926   938 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 18:33:57.799   926   938 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:33:57.799   926   938 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 18:33:57.799   926   938 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
11-22 18:33:57.799   926   938 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
11-22 18:33:57.799   926   938 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
11-22 18:33:57.799   926   938 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-22 18:33:57.799   926   938 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-22 18:33:57.799   926   938 E PackageManager: 	... 12 more
,11-22 18:33:57.807    28    28 W kworker/3:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 18:33:57.812  3589  5980 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-22 18:33:57.816   926  3744 I ActivityManager: Start proc 5988:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-22 18:33:57.817  3748  3846 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-22 18:33:57.817  3748  3846 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3748
11-22 18:33:57.817  3748  3846 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-22 18:33:57.817  3748  3846 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 18:33:57.817  3748  3846 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 18:33:57.817  3748  3846 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 18:33:57.817  3748  3846 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 18:33:57.817  3748  3846 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 18:33:57.817  3748  3846 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-22 18:33:57.817  3748  3846 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-22 18:33:57.817  3748  3846 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-22 18:33:57.817  3748  3846 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-22 18:33:57.817  3748  3846 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:33:57.817  3748  3846 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-22 18:33:57.824   926  3357 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-22 18:33:57.829  3900  4048 W SearchService: Abort, client detached.
,11-22 18:33:57.832  3340  5984 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-22 18:33:57.833  3900  3900 I HotwordDetector: Closing mic
11-22 18:33:57.833  3900  4134 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@400bd82
11-22 18:33:57.833  3900  5962 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-22 18:33:57.835   926  5996 E DropBoxManagerService: Can't write: system_app_crash
11-22 18:33:57.835   926  5996 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-22 18:33:57.835   926  5996 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 18:33:57.835   926  5996 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 18:33:57.835   926  5996 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 18:33:57.835   926  5996 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 18:33:57.835   926  5996 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 18:33:57.835   926  5996 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 18:33:57.835   926  5996 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 18:33:57.835   926  5996 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 18:33:57.835   926  5996 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 18:33:57.835   926  5996 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 18:33:57.835   926  5996 E DropBoxManagerService: 	... 5 more
11-22 18:33:57.840   404   404 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[36872]" dev="sockfs" ino=36872 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 18:33:57.840   404   404 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[36872]" dev="sockfs" ino=36872 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 18:33:57.840   404   404 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[35902]" dev="sockfs" ino=35902 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 18:33:57.845   926  6001 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-22 18:33:57.840   404   404 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[35902]" dev="sockfs" ino=35902 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 18:33:57.845  3340  5984 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-22 18:33:57.845  3340  5984 E AndroidRuntime: Process: android.process.acore, PID: 3340
11-22 18:33:57.845  3340  5984 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:33:57.845  3340  5984 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-22 18:33:57.859   926  6002 E DropBoxManagerService: Can't write: system_app_crash
11-22 18:33:57.859   926  6002 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-22 18:33:57.859   926  6002 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 18:33:57.859   926  6002 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 18:33:57.859   926  6002 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 18:33:57.859   926  6002 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 18:33:57.859   926  6002 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 18:33:57.859   926  6002 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 18:33:57.859   926  6002 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 18:33:57.859   926  6002 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 18:33:57.859   926  6002 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 18:33:57.859   926  6002 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 18:33:57.859   926  6002 E DropBoxManagerService: 	... 5 more
,11-22 18:33:57.862  3521  3521 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-22 18:33:57.864  3521  3521 D AndroidRuntime: Shutting down VM
,11-22 18:33:57.865  3521  3521 E AndroidRuntime: FATAL EXCEPTION: main
11-22 18:33:57.865  3521  3521 E AndroidRuntime: Process: com.google.process.gapps, PID: 3521
11-22 18:33:57.865  3521  3521 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-22 18:33:57.865  3521  3521 E AndroidRuntime: 	... 8 more
,11-22 18:33:57.869   926  6004 E DropBoxManagerService: Can't write: system_app_crash
11-22 18:33:57.869   926  6004 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-22 18:33:57.869   926  6004 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 18:33:57.869   926  6004 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 18:33:57.869   926  6004 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 18:33:57.869   926  6004 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 18:33:57.869   926  6004 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 18:33:57.869   926  6004 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 18:33:57.869   926  6004 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 18:33:57.869   926  6004 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 18:33:57.869   926  6004 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 18:33:57.869   926  6004 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 18:33:57.869   926  6004 E DropBoxManagerService: 	... 5 more
,11-22 18:33:57.889  3589  5980 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-22 18:33:57.891   926  6001 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-22 18:33:57.891   926  6001 I Adreno  : Build Date                       : 12/06/15
11-22 18:33:57.891   926  6001 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-22 18:33:57.891   926  6001 I Adreno  : Local Branch                     : mybranch17112971
11-22 18:33:57.891   926  6001 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-22 18:33:57.891   926  6001 I Adreno  : Remote Branch                    : NONE
11-22 18:33:57.891   926  6001 I Adreno  : Reconstruct Branch               : NOTHING
11-22 18:33:57.892  3589  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-22 18:33:57.892  3589  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-22 18:33:57.896   513  5964 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-22 18:33:57.897   513  5964 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-22 18:33:57.898  3589  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-22 18:33:57.898  3589  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-22 18:33:57.899  3589  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-22 18:33:57.899  3589  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-22 18:33:57.900  3589  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-22 18:33:57.900  3589  5980 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-22 18:33:57.900  3589  5980 I Keyboard.Facilitator.Delight2FileSweeper: run()
,11-22 18:33:57.900  3589  5980 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-22 18:33:57.900  3589  5980 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-22 18:33:57.900  3589  5980 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-22 18:33:57.901   513  5964 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-22 18:33:57.902   513  5964 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-22 18:33:57.903   513  2931 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-22 18:33:57.905  3900  5961 I MicroRecognitionRnrImpl: Detection finished
11-22 18:33:57.905  3900  4137 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-22 18:33:58.218   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
