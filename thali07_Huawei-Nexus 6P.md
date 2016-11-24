#### Test 950476159fe9405_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-24 11:23:21.551   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:23:22.036  5547  5547 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 11:23:22.043  5547  5547 D AndroidRuntime: CheckJNI is OFF
11-24 11:23:22.077  5547  5547 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 11:23:22.113  5547  5547 I Radio-JNI: register_android_hardware_Radio DONE
11-24 11:23:22.128  5547  5547 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-24 11:23:22.132   926  3818 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 11:23:22.151  5547  5547 D AndroidRuntime: Shutting down VM
11-24 11:23:22.162  3942  3956 W SearchService: Abort, client detached.
11-24 11:23:22.165  3942  4158 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d52e958
11-24 11:23:22.165  3942  4161 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-24 11:23:22.165  3942  3942 I HotwordDetector: Closing mic
11-24 11:23:22.179   926  3771 I ActivityManager: Start proc 5556:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 11:23:22.231   513  4164 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-24 11:23:22.232   513  4164 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-24 11:23:22.235   513  4164 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-24 11:23:22.235   513  4164 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-24 11:23:22.235   513  2971 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 11:23:22.237  3942  4159 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-24 11:23:22.237  3942  4160 I MicroRecognitionRnrImpl: Detection finished
11-24 11:23:22.277  5556  5556 I CordovaLog: Changing log level to DEBUG(3)
11-24 11:23:22.277  5556  5556 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 11:23:22.277  5556  5556 D CordovaActivity: CordovaActivity.onCreate()
11-24 11:23:22.281  5556  5556 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-24 11:23:22.301  5556  5556 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-24 11:23:22.322  5556  5556 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 4823-4841)
11-24 11:23:22.322  5556  5556 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-24 11:23:22.339  5556  5556 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b45001f}
11-24 11:23:22.339  5556  5556 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-24 11:23:22.339  5556  5556 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-24 11:23:22.342  5556  5556 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-24 11:23:22.343  5556  5556 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 11:23:22.376  5556  5556 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 11:23:22.389  5556  5556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 11:23:22.389  5556  5556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 11:23:22.389  5556  5556 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 11:23:22.389  5556  5556 I Adreno  : Build Date                       : 12/06/15
11-24 11:23:22.389  5556  5556 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 11:23:22.389  5556  5556 I Adreno  : Local Branch                     : mybranch17112971
11-24 11:23:22.389  5556  5556 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 11:23:22.389  5556  5556 I Adreno  : Remote Branch                    : NONE
11-24 11:23:22.389  5556  5556 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 11:23:22.420   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@657fc26:true
,11-24 11:23:22.443   406   406 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[21898]" dev="sockfs" ino=21898 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:23:22.443   406   406 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[21898]" dev="sockfs" ino=21898 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:23:22.453  5556  5556 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 11:23:22.461  5556  5556 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 11:23:22.464  5556  5556 D PluginManager: init()
,11-24 11:23:22.467  5556  5556 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 11:23:22.480  5556  5556 D CordovaActivity: Started the activity.
,11-24 11:23:22.480  5556  5556 D CordovaActivity: Resumed the activity.
,11-24 11:23:22.480   949   949 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33832]" dev="sockfs" ino=33832 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 11:23:22.483  5556  5593 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 11:23:22.480   949   949 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33832]" dev="sockfs" ino=33832 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:23:22.483  3567  3567 W Binder_6: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34918]" dev="sockfs" ino=34918 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 11:23:22.487  5556  5580 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-24 11:23:22.483  3567  3567 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[34918]" dev="sockfs" ino=34918 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 11:23:22.512  5556  5593 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 11:23:22.552   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:23:22.580   936   936 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32989]" dev="sockfs" ino=32989 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 11:23:22.580   936   936 W Binder_1: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32989]" dev="sockfs" ino=32989 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 11:23:22.580   936   936 W Binder_1: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32988]" dev="sockfs" ino=32988 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 11:23:22.580   936   936 W Binder_1: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32988]" dev="sockfs" ino=32988 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 11:23:22.582   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +419ms
11-24 11:23:22.587  3639  3639 I Keyboard.Facilitator: onFinishInput()
,11-24 11:23:22.601  5556  5556 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 11:23:22.631  5556  5556 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5556
,11-24 11:23:22.718  5556  5556 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 11:23:22.851  5556  5595 D jxcore_app_log: JniHelper::setJavaVM(0xf55fc000), pthread_self() = -576980688
,11-24 11:23:22.854  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 11:23:22.854  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 11:23:22.854  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 11:23:22.854  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 11:23:22.854  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-24 11:23:22.855  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ecbad added. We now have 1 listener(s)
,11-24 11:23:22.857  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-24 11:23:22.857  5556  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 11:23:22.857  5556  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:23:22.858  5556  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-24 11:23:22.860  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b163530 added. We now have 1 listener(s)
,11-24 11:23:22.860  5556  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:23:22.865   926  2924 D WifiService: New client listening to asynchronous messages
,11-24 11:23:22.865  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 11:23:22.865  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-24 11:23:22.866  5556  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 11:23:22.866  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 11:23:22.866  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-24 11:23:22.866  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-24 11:23:22.866  5556  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-24 11:23:22.867  5556  5595 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 11:23:22.876  5556  5556 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 11:23:22.881  5556  5556 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-24 11:23:22.881  5556  5556 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 11:23:22.981   926  3771 I ActivityManager: Killing 5009:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-24 11:23:23.013   926  3771 I ActivityManager: Killing 5233:com.android.settings/1000 (adj 15): empty #18
,11-24 11:23:23.445  5556  5602 W jxcore-log: Initializing JXcore engine
,11-24 11:23:23.445  5556  5602 W jxcore-log: JXcore engine is ready
,11-24 11:23:23.467  5602  5602 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11819 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 11:23:23.467  5602  5602 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[12963]" dev="sockfs" ino=12963 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-24 11:23:23.467  5602  5602 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-24 11:23:23.470  5602  5602 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31123]" dev="sockfs" ino=31123 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 11:23:23.479  5556  5602 W jxcore-log: Starting JXcore engine
,11-24 11:23:23.529  5556  5602 W jxcore-log: Platform android
11-24 11:23:23.529  5556  5602 W jxcore-log: 
,11-24 11:23:23.529  5556  5602 W jxcore-log: Process ARCH arm
11-24 11:23:23.529  5556  5602 W jxcore-log: 
,11-24 11:23:23.553   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:23:23.716  5556  5602 I jxcore-log: JXcore Cordova bridge is ready!
11-24 11:23:23.716  5556  5602 I jxcore-log: 
,11-24 11:23:23.716  5556  5602 W jxcore-log: JXcore engine is started
,11-24 11:23:23.728  5556  5595 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-24 11:23:23.735  5556  5556 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-24 11:23:23.735  5556  5556 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 11:23:24.554   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:23:25.556   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:23:26.557   556   556 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 11:23:32.343   926  2924 D WifiService: New client listening to asynchronous messages
,11-24 11:23:32.347  3942  5605 W CronetSyncConnectionRcs: Upload content type not set.
,11-24 11:23:33.451  5556  5602 I jxcore-log: 2016-11-24 10:23:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 11:23:33.451  5556  5602 I jxcore-log: 
,11-24 11:23:33.453  5556  5602 I jxcore-log: 2016-11-24 10:23:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 11:23:33.453  5556  5602 I jxcore-log: 
,11-24 11:23:33.460  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-24 11:23:33.460  5556  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 11:23:33.460  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:23:33.460  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:23:33.460  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:23:33.460  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:23:33.460  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 11:23:33.460  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 11:23:33.460  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:23:33.460  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 11:23:33.462  5556  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 11:23:33.464  5556  5602 I jxcore-log: 2016-11-24 10:23:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 11:23:33.464  5556  5602 I jxcore-log: 
11-24 11:23:33.465  5556  5602 I jxcore-log: 2016-11-24 10:23:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 11:23:33.465  5556  5602 I jxcore-log: 
,11-24 11:23:33.712  5556  5602 I jxcore-log: 2016-11-24 10:23:33 - DEBUG UnitTest_app: 'Running unit tests'
11-24 11:23:33.712  5556  5602 I jxcore-log: 
,11-24 11:23:33.713  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:23:33.713  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e0f55 added. We now have 2 listener(s)
11-24 11:23:33.714  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:23:33.714  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 11:23:33.714  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:23:33.714  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:23:33.714  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb69d6a added. We now have 2 listener(s)
,11-24 11:23:33.714  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:23:33.715  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 11:23:33.719  5556  5602 D executeNativeTests: Running unit tests
,11-24 11:23:33.757  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 11:23:33.757  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b added. We now have 3 listener(s)
,11-24 11:23:33.758  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 11:23:33.758  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:23:33.758  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:23:33.758  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:23:33.758  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 added. We now have 3 listener(s)
11-24 11:23:33.758  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:23:33.759  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 11:23:33.760  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 11:23:33.760  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 11:23:33.760  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 11:23:33.761  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 11:23:33.761  5556  5602 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 11:23:33.761  5556  5602 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 11:23:33.761  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 11:23:33.761  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 11:23:33.761  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 11:23:33.762  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 11:23:33.762  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:33.762  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:33.762  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:33.762  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:33.762  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:23:33.763  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:23:33.763  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b removed from the list
11-24 11:23:33.763  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:33.763  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 removed from the list
11-24 11:23:33.763  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:23:33.763  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.763  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.763  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.763  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.764  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.764  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:33.764  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:33.764  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:33.764  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:33.764  5556  5602 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-24 11:23:33.765  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:33.765  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:33.765  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:33.765  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:33.765  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:33.765  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:33.765  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:33.765  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:33.765  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:33.765  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.765  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.766  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.766  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.766  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.766  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:33.766  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:33.766  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:33.766  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:33.768  5556  5602 D, io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 11:23:33.768  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 11:23:33.768  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 11:23:33.768  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 11:23:33.768  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 11:23:33.768  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 11:23:33.768  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-24 11:23:33.768  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 11:23:33.768  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 11:23:33.768  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 11:23:33.768  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 11:23:33.768  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
11-24 11:23:33.769  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:33.769  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:33.769  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:33.769  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:33.769  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:33.769  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:33.769  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:33.769  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:33.769  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:33.769  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.769  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.770  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.770  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.770  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.770  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:33.770  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:33.770  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:33.770  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:33.770  5556  5602 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 11:23:33.772  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:23:33.772  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 11:23:33.775  5556  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 11:23:33.775  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:23:33.775  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:23:33.775  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:23:33.775  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:23:33.775  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 11:23:33.775  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 11:23:33.775  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:23:33.775  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 11:23:33.775  5556  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 11:23:33.776  5556  5602 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 11:23:33.776  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:23:33.776  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 11:23:33.776  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 11:23:33.776  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:23:33.776  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 11:23:33.778  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:23:33.779  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 11:23:33.779  5556  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 11:23:33.779  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 11:23:33.779  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:23:33.781  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.781  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 11:23:33.782  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 11:23:33.782  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 11:23:33.782  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 11:23:33.783  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-24 11:23:33.784  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-24 11:23:33.785  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.785  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 11:23:33.785  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 11:23:33.785  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:23:33.785  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:23:33.785  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.786  5556  5602 D BluetoothAdapter: STATE_ON
11-24 11:23:33.788  4624  4845 D BtGatt.GattService: registerClient() - UUID=ad81109a-3000-4583-b77d-48e401cf5f1f
11-24 11:23:33.790  4624  4686 D BtGatt.GattService: onClientRegistered() - UUID=ad81109a-3000-4583-b77d-48e401cf5f1f, clientIf=5
11-24 11:23:33.792  5556  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 11:23:33.793  4624  4638 D BtGatt.GattService: start scan with filters
11-24 11:23:33.799  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 11:23:33.799  4624  4691 D BtGatt.ScanManager: handling starting scan
11-24 11:23:33.799  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.799  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 11:23:33.800  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.800  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 11:23:33.800  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 11:23:33.800  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.800  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 11:23:33.801  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:23:33.801  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:23:33.801  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 11:23:33.801  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:23:33.801  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.801  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.801  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:23:33.801  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:33.801  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:23:33.802  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 11:23:33.802  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:23:33.802  5556  5602 I io.jxcore.node.ConnectionHelper: start: OK
11-24 11:23:33.805  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:23:33.805  4624  4691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
11-24 11:23:33.805  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:23:33.805  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:23:33.805  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:23:33.806  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:23:33.813  4624  4686 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 11:23:33.813  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:33.813  4624  4691 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 11:23:33.820  4624  4686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 11:23:33.820  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:33.820  4624  4691 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:23:33.820  4624  4691 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 11:23:33.832  4624  4686 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 11:23:33.832  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:33.838  4624  4686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 11:23:33.838  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:23:34.307  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 11:23:34.308  5556  5556 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:23:34.308  5556  5556 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 11:23:34.422   926  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 11:23:37.399   926  5323 D NetlinkSocketObserver: NeighborEvent{elapsedMs=179917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 11:23:38.412   926  2923 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:23:38.806  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:23:38.806  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:38.807  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 11:23:38.807  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 11:23:38.807  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-24 11:23:38.807  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:38.807  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 11:23:38.807  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:23:38.807  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:38.807  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 11:23:38.808  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:23:38.808  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.809  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:38.809  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.809  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 11:23:38.809  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.810  5556  5602 D BluetoothAdapter: STATE_ON
,11-24 11:23:38.810  4624  4637 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 11:23:38.811  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 11:23:38.812  5556  5602 D BluetoothAdapter: STATE_ON
11-24 11:23:38.812  4624  4691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:23:38.813  4624  4638 D BtGatt.GattService: stopScan() - queue size =1
,11-24 11:23:38.813  4624  4847 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 11:23:38.814  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 11:23:38.814  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.814  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:23:38.814  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.814  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.814  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.815  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.815  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-24 11:23:38.815  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.815  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.815  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.815  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:23:38.816  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 11:23:38.816  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:23:38.817  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.818  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.818  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:23:38.818  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.818  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:38.819  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:38.819  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:23:38.819  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 11:23:38.819  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:38.819  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:38.819  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:38.819  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:38.819  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:23:38.819  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:23:38.819  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:23:38.819  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:23:38.820  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:23:38.820  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:23:38.820  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-24 11:23:38.820  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:23:38.821  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:23:38.821  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:23:38.821  4624  4624 D BtGatt.ScanManager: awakened up at time 181339
11-24 11:23:38.821  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 11:23:38.821  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:23:38.822  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:23:38.822  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:23:38.827  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 11:23:38.827  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:23:38.827  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 11:23:38.849  4624  4686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-24 11:23:38.849  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:38.849  4624  4686 D BtGatt.GattService: current time is 181367802278
11-24 11:23:38.850  4624  4686 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -90, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -87, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -86, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -95, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 11:23:38.851  4624  4686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-24 11:23:38.853  4624  4686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 11:23:38.853  4624  4686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-24 11:23:38.854  4624  4686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 11:23:38.854  4624  4686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-24 11:23:38.861  4624  4686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 11:23:38.861  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:38.862  4624  4691 D BtGatt.ScanManager: stopping BLe Batch
,11-24 11:23:38.869  4624  4686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 11:23:38.869  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:38.869  4624  4691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:23:38.877  4624  4686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:23:38.877  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:23:39.322  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 11:23:40.469   926  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 11:23:43.828  5556  5602 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 11:23:43.835  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 11:23:43.836  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 11:23:43.849  5556  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 11:23:43.849  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:23:43.849  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:23:43.849  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:23:43.849  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:23:43.849  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 11:23:43.849  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 11:23:43.849  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:23:43.849  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 11:23:43.854  5556  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 11:23:43.854  5556  5602 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 11:23:43.854  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:23:43.855  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 11:23:43.855  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 11:23:43.855  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:23:43.855  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 11:23:43.862  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:23:43.863  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 11:23:43.864  5556  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 11:23:43.864  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 11:23:43.868  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:23:43.869  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.869  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 11:23:43.870  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 11:23:43.870  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 11:23:43.870  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 11:23:43.877  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:43.877  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 11:23:43.877  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 11:23:43.877  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:23:43.877  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:23:43.877  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.879  5556  5602 D BluetoothAdapter: STATE_ON
,11-24 11:23:43.882  4624  4638 D BtGatt.GattService: registerClient() - UUID=407eff3d-1ae1-4785-b826-7315e0696fce
11-24 11:23:43.883  4624  4686 D BtGatt.GattService: onClientRegistered() - UUID=407eff3d-1ae1-4785-b826-7315e0696fce, clientIf=5
,11-24 11:23:43.883  5556  5566 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 11:23:43.884  4624  4847 D BtGatt.GattService: start scan with filters
11-24 11:23:43.887  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 11:23:43.888  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:43.888  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 11:23:43.888  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.888  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 11:23:43.889  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 11:23:43.889  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 11:23:43.889  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:23:43.889  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 11:23:43.889  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.889  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.889  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.889  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.890  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-24 11:23:43.890  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.891  4624  4691 D BtGatt.ScanManager: handling starting scan
,11-24 11:23:43.900  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:43.900  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:23:43.900  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.900  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.900  5556  5602 I io.jxcore.node.ConnectionHelper: start: OK
11-24 11:23:43.900  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.901  4624  4686 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 11:23:43.901  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:43.902  4624  4691 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 11:23:43.904  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:43.904  5556  5602 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 11:23:43.904  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.904  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.904  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:43.904  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 11:23:43.904  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.904  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:23:43.904  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 11:23:43.904  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:23:43.904  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:43.905  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 11:23:43.905  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:23:43.905  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.905  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 11:23:43.905  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:23:43.905  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.905  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.905  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.905  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 11:23:43.905  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.906  5556  5602 D BluetoothAdapter: STATE_ON
11-24 11:23:43.907  4624  4834 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-24 11:23:43.907  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 11:23:43.907  5556  5602 D BluetoothAdapter: STATE_ON
11-24 11:23:43.908  4624  4638 D BtGatt.GattService: stopScan() - queue size =1
11-24 11:23:43.909  4624  4686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 11:23:43.909  4624  4847 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-24 11:23:43.909  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:43.909  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 11:23:43.909  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.909  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:23:43.909  4624  4691 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:23:43.909  4624  4691 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 11:23:43.909  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.909  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.909  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.909  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.909  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 11:23:43.909  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.909  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.910  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:43.910  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:23:43.910  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 11:23:43.910  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:23:43.910  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.911  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.911  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:23:43.911  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.912  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.912  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:43.912  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:23:43.912  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:23:43.912  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:43.912  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:23:43.912  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:43.912  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 11:23:43.912  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:43.912  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:43.912  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:23:43.912  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:43.912  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:23:43.912  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.912  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 11:23:43.912  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:23:43.912  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.913  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.913  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.913  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:23:43.913  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.913  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:43.914  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:43.915  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.915  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.915  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:43.915  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:43.915  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:43.915  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:43.915  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:43.915  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.916  5556  5602 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 11:23:43.916  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.916  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-24 11:23:43.916  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.917  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:23:43.918  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 11:23:43.921  4624  4686 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 11:23:43.921  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:23:43.925  5556  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 11:23:43.925  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:23:43.925  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:23:43.925  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:23:43.925  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:23:43.925  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 11:23:43.925  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 11:23:43.925  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:23:43.925  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 11:23:43.927  4624  4686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 11:23:43.927  5556  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 11:23:43.927  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:43.927  5556  5602 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 11:23:43.927  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 11:23:43.927  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-24 11:23:43.928  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 11:23:43.928  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:23:43.928  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 11:23:43.929  4624  4691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:23:43.935  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 11:23:43.935  5556  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 11:23:43.935  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 11:23:43.936  4624  4686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:23:43.936  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:43.936  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:23:43.936  4624  4686 E BtGatt.ContextMap: Context not found for ID 5
,11-24 11:23:43.939  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:23:43.939  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.939  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 11:23:43.939  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 11:23:43.939  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-24 11:23:43.939  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 11:23:43.942  4624  4686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 11:23:43.942  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:43.942  4624  4691 D BtGatt.ScanManager: stopping BLe Batch
,11-24 11:23:43.943  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.943  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 11:23:43.943  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 11:23:43.943  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:23:43.943  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:23:43.943  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.943  5556  5602 D BluetoothAdapter: STATE_ON
,11-24 11:23:43.945  4624  4847 D BtGatt.GattService: registerClient() - UUID=a557a8cf-6f0e-4462-a386-4c9fa3fb6f8f
11-24 11:23:43.946  4624  4686 D BtGatt.GattService: onClientRegistered() - UUID=a557a8cf-6f0e-4462-a386-4c9fa3fb6f8f, clientIf=5
,11-24 11:23:43.946  5556  5566 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 11:23:43.946  4624  4686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 11:23:43.946  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:43.946  4624  4691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 11:23:43.946  4624  4834 D BtGatt.GattService: start scan with filters
,11-24 11:23:43.949  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 11:23:43.949  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.949  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 11:23:43.949  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.949  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 11:23:43.949  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 11:23:43.949  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.949  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:23:43.949  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 11:23:43.949  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 11:23:43.949  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.949  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.949  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.950  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 11:23:43.950  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.951  4624  4686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:23:43.951  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:43.952  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.952  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 11:23:43.952  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.952  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:43.952  5556  5602 I io.jxcore.node.ConnectionHelper: start: OK
11-24 11:23:43.952  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.953  4624  4691 D BtGatt.ScanManager: handling starting scan
,11-24 11:23:43.955  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 11:23:43.955  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.955  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:23:43.955  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 11:23:43.960  4624  4686 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 11:23:43.960  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:43.960  4624  4691 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 11:23:43.965  4624  4686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-24 11:23:43.965  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:43.965  4624  4691 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:23:43.965  4624  4691 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 11:23:43.973  4624  4686 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 11:23:43.973  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:23:43.978  4624  4686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 11:23:43.978  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:23:44.457  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 11:23:44.457  5556  5556 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 11:23:44.457  5556  5556 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 11:23:46.558   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:23:47.559   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:23:48.560   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:23:48.953  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:23:48.953  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:23:48.953  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 11:23:48.953  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:23:48.954  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 11:23:48.954  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:48.954  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 11:23:48.954  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:23:48.954  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.955  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 11:23:48.955  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:23:48.955  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.955  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.956  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.956  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 11:23:48.956  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.958  5556  5602 D BluetoothAdapter: STATE_ON
11-24 11:23:48.959  4624  4847 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 11:23:48.959  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 11:23:48.960  4624  4691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 11:23:48.961  5556  5602 D BluetoothAdapter: STATE_ON
,11-24 11:23:48.962  4624  4638 D BtGatt.GattService: stopScan() - queue size =1
11-24 11:23:48.964  4624  4845 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 11:23:48.965  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 11:23:48.965  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.966  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:23:48.966  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.966  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:48.966  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.966  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.967  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 11:23:48.967  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.967  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.967  4624  4624 D BtGatt.ScanManager: awakened up at time 191485
11-24 11:23:48.967  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.967  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:23:48.968  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 11:23:48.972  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:23:48.972  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.974  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.974  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:23:48.974  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.975  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:48.975  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:23:48.975  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 11:23:48.975  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:23:48.975  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:23:48.975  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 11:23:48.976  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:23:48.976  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:23:48.976  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:23:48.976  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:23:48.976  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 11:23:48.976  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:23:48.976  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:23:48.979  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:23:48.979  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:23:48.979  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 11:23:48.993  4624  4686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-24 11:23:48.994  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:48.994  4624  4686 D BtGatt.GattService: current time is 191512606632
11-24 11:23:48.994  4624  4686 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -93, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -85, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -90, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -78, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -88, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 11:23:48.995  4624  4686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 11:23:48.995  4624  4686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-24 11:23:48.995  4624  4686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 11:23:48.996  4624  4686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-24 11:23:48.996  4624  4686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 11:23:48.996  4624  4686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 11:23:49.003  4624  4686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 11:23:49.003  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:49.003  4624  4691 D BtGatt.ScanManager: stopping BLe Batch
,11-24 11:23:49.009  4624  4686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 11:23:49.009  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:23:49.010  4624  4691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:23:49.017  4624  4686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:23:49.017  4624  4686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:23:49.478  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 11:23:49.478  5556  5556 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:23:49.479  5556  5556 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 11:23:49.561   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:23:50.562   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:23:51.563   556   556 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 11:23:53.976  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:23:53.977  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:23:53.977  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 11:23:53.977  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:23:53.977  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 11:23:53.977  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:23:53.977  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:23:53.978  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:53.978  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:23:53.978  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:53.978  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:23:53.979  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:23:53.981  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.981  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:53.984  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.984  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.985  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.985  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 11:23:53.985  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:53.985  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:53.985  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:53.987  5556  5602 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-24 11:23:53.988  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:53.989  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:53.989  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 11:23:53.989  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:53.989  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:53.989  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:53.989  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:53.990  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:53.990  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:23:53.990  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.990  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.993  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.993  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.993  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.993  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 11:23:53.993  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:53.994  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:53.994  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
,11-24 11:23:53.996  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 11:23:53.996  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:53.996  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:53.996  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 11:23:53.996  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:53.996  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:53.996  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:53.997  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:23:53.997  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:53.997  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:53.997  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.997  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:53.999  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.999  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.999  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:53.999  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 11:23:53.999  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:53.999  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:53.999  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.000  5556  5602 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 11:23:54.000  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:23:54.000  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:54.000  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:54.000  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:54.000  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:54.001  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
,11-24 11:23:54.001  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:54.001  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.001  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:54.001  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.001  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.003  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:54.003  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.003  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.003  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:54.003  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:54.003  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:23:54.003  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.004  5556  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-24 11:23:54.004  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:54.004  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:54.004  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:54.005  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:54.005  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:54.005  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
,11-24 11:23:54.005  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:23:54.005  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
,11-24 11:23:54.005  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop,
11-24 11:23:54.005  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.005  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:54.006  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.007  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.007  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:54.007  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:54.007  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:54.007  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:54.007  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.008  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 11:23:54.008  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 11:23:54.008  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 11:23:54.008  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 11:23:54.008  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 11:23:54.008  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 11:23:54.008  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 11:23:54.008  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 11:23:54.009  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 11:23:54.009  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:23:54.009  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:54.009  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:54.009  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:54.009  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:54.009  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:54.009  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:54.009  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
,11-24 11:23:54.009  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:54.009  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.010  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.011  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.011  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.011  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.011  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:54.011  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 11:23:54.011  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:54.011  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.012  5556  5602 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 11:23:54.012  5556  5602 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 11:23:54.012  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 11:23:54.016  5556  5602 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 11:23:54.016  5556  5602 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 11:23:54.016  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 11:23:54.016  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 11:23:54.016  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 11:23:54.016  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 11:23:54.016  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-24 11:23:54.016  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 11:23:54.016  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 11:23:54.017  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 11:23:54.018  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 11:23:54.018  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 11:23:54.018  5556  5602 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-24 11:23:54.018  5556  5602 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 11:23:54.018  5556  5602 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-24 11:23:54.018  5556  5602 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 11:23:54.018  5556  5602 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 11:23:54.018  5556  5602 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 11:23:54.018  5556  5602 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 11:23:54.018  5556  5602 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 11:23:54.019  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-24 11:23:54.026  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-24 11:23:54.027  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 11:23:54.027  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-24 11:23:54.028  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionMan,ager: onConnecting: null 00:11:22:33:44:55
11-24 11:23:54.028  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 11:23:54.028  5556  5602 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-24 11:23:54.028  5556  5602 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 11:23:54.028  5556  5602 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-24 11:23:54.028  5556  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
,11-24 11:23:54.029  5556  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-24 11:23:54.029  5556  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 11:23:54.029  5556  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-24 11:23:54.029  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:54.029  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:23:54.029  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:54.029  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:23:54.029  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:23:54.030  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 11:23:54.030  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:54.031  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:54.031  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.031  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:54.031  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.031  5556  5617 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 11:23:54.031  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.031  5556  5617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:23:54.032  5556  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
,11-24 11:23:54.032  5556  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-24 11:23:54.032  5556  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
11-24 11:23:54.032  5556  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
11-24 11:23:54.030  4834  4834 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33017]" dev="sockfs" ino=33017 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 11:23:54.034  5556  5617 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-24 11:23:54.034  5556  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 11:23:54.034  5556  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
11-24 11:23:54.030  4834  4834 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33017]" dev="sockfs" ino=33017 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 11:23:54.035  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.035  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:54.035  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.035  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:54.035  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:54.035  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:54.035  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.036  5556  5602 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-24 11:23:54.036  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:54.037  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:54.037  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:54.037  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:54.037  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:23:54.037  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:54.037  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:54.037  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.037  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:54.037  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.037  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.038  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.038  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.038  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.038  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:54.038  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:54.038  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:23:54.038  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.039  5556  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 11:23:54.039  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:54.040  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:54.040  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:54.040  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:54.040  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:54.040  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:54.040  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:54.040  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
,11-24 11:23:54.040  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:54.040  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.040  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.042  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.042  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.042  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:54.042  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:54.042  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:54.042  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:54.042  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.043  5556  5602 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 11:23:54.043  5556  5602 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-24 11:23:54.043  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 11:23:54.043  5556  5602 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-24 11:23:54.043  5556  5602 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 11:23:54.043  5556  5602 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-24 11:23:54.043  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 11:23:54.043  5556  5602 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 11:23:54.043  5556  5602 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 11:23:54.043  5556  5602 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 11:23:54.043  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 11:23:54.043  5556  5602 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-24 11:23:54.043  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:54.043  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:54.044  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:54.044  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:54.044  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:23:54.044  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:54.044  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:54.044  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.044  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:54.044  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.044  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.045  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.045  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:54.045  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:54.045  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:54.045  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:54.045  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:54.046  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.046  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:54.046  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:54.046  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:54.046  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:23:54.046  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:54.046  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:23:55.603   926  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 11:23:58.414   926  2923 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:23:59.047  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:23:59.048  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:59.048  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:59.048  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:59.048  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
,11-24 11:23:59.049  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:59.049  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:59.049  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:59.049  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:23:59.049  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:59.050  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:59.050  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:59.050  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:59.050  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:59.050  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:59.051  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:59.056  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:59.056  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.056  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.056  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:59.057  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 11:23:59.057  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:59.057  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:59.060  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-24 11:23:59.060  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:23:59.061  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 11:23:59.066  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-24 11:23:59.068  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-24 11:23:59.068  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-24 11:23:59.068  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-24 11:23:59.069  5556  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-24 11:23:59.069  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-24 11:23:59.069  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 11:23:59.069  5556  5556 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-24 11:23:59.070  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:59.070  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-24 11:23:59.070  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-24 11:23:59.070  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-24 11:23:59.070  5556  5619 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:23:59.070  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 11:23:59.072  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 11:23:59.072  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-24 11:23:59.072  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:59.072  5556  5556 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-24 11:23:59.072  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:59.073  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:23:59.073  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.073  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 11:23:59.073  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:23:59.073  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.075  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.075  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:23:59.073  4638  4638 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32571]" dev="sockfs" ino=32571 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 11:23:59.075  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:59.075  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.073  4638  4638 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32571]" dev="sockfs" ino=32571 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 11:23:59.076  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:59.076  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:59.076  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 11:23:59.076  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:59.076  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:23:59.076  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:59.076  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:23:59.076  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:59.076  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-24 11:23:59.076  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:59.076  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:59.076  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:59.077  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:59.077  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.077  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:59.079  5556  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-24 11:23:59.079  5556  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-24 11:23:59.079  5556  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-24 11:23:59.080  5556  5556 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 11:23:59.080  5556  5556 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:23:59.081  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.081  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.081  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.081  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:59.081  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 11:23:59.081  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:59.082  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
,11-24 11:23:59.083  5556  5602 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-24 11:23:59.084  5556  5602 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 11:23:59.084  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 11:23:59.084  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 11:23:59.084  5556  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 11:23:59.084  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:59.085  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:59.085  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:59.085  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:23:59.085  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:59.085  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:59.085  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:59.085  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:59.085  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:59.086  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.086  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:59.089  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:59.089  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.089  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.089  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:59.089  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:59.089  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:59.089  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
,11-24 11:23:59.096  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:23:59.096  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:59.096  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 11:23:59.096  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:23:59.096  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:59.096  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:59.096  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:59.096  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:59.096  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:23:59.096  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:23:59.097  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.098  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.098  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.098  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.098  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:23:59.098  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 11:23:59.098  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:59.098  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:59.099  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:23:59.099  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:23:59.099  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:23:59.100  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:23:59.100  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:23:59.100  5556  5602 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@815b84b not in the list
11-24 11:23:59.100  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:59.100  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
11-24 11:23:59.100  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:23:59.100  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.100  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.101  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.102  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.102  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:23:59.102  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 11:23:59.102  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:23:59.102  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:23:59.102  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4688228 not in the list
,11-24 11:23:59.103  5556  5602 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-24 11:23:59.103  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 11:23:59.103  5556  5602 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 11:23:59.103  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 11:23:59.104  5556  5602 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-24 11:23:59.104  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 11:23:59.106  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 11:23:59.106  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-24 11:23:59.107  5556  5602 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-24 11:23:59.107  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 11:23:59.107  5556  5602 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 11:23:59.107  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 11:23:59.107  5556  5602 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 11:23:59.107  5556  5602 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 11:23:59.108  5556  5602 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-24 11:23:59.108  5556  5602 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-24 11:23:59.109  5556  5602 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-24 11:23:59.109  5556  5602 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-24 11:23:59.109  5556  5602 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-24 11:23:59.109  5556  5602 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-24 11:23:59.110  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:23:59.110  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c906b1 added. We now have 3 listener(s)
11-24 11:23:59.110  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:23:59.111  5556  5602 D BluetoothAdapter: enable(): BT is already enabled..!
,11-24 11:23:59.112   926   936 D WifiService: setWifiEnabled: true pid=5556, uid=10077
11-24 11:23:59.112   926   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 11:23:59.161  4624  4825 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-24 11:23:59.161  4624  4832 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-24 11:23:59.576  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 11:24:01.639   926  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 11:24:02.439   926  5323 D NetlinkSocketObserver: NeighborEvent{elapsedMs=204957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 11:24:04.117  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 11:24:04.117  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a87f796 added. We now have 4 listener(s)
11-24 11:24:04.118  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:24:04.130  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:24:04.130  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a87f796 removed from the list
,11-24 11:24:04.130  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:24:04.132  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:04.132  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d584f17 added. We now have 4 listener(s)
,11-24 11:24:04.133  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:24:04.138  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:24:04.139  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d584f17 removed from the list
11-24 11:24:04.139  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:24:04.140  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 11:24:04.140  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@97cdf04 added. We now have 4 listener(s)
11-24 11:24:04.141  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:24:04.145   926  3567 D WifiService: setWifiEnabled: false pid=5556, uid=10077
,11-24 11:24:04.145   926  3567 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 11:24:04.149   926  2923 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 11:24:04.149   926  2923 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 11:24:04.149   926  2923 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 11:24:04.150   926  2923 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:24:04.156  4624  4682 D BluetoothAdapterState: Current state: ON, message: 23
11-24 11:24:04.156  4624  4682 D BluetoothAdapterProperties: Setting state to 13
,11-24 11:24:04.156  4624  4682 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 11:24:04.158  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 11:24:04.158  4624  4682 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 11:24:04.158  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 11:24:04.159  4624  4682 I BluetoothAdapterState: Entering PendingCommandState
,11-24 11:24:04.164  4624  4624 D BluetoothMapService: onReceive
11-24 11:24:04.164  4624  4624 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 11:24:04.164  4624  4624 D BluetoothMapService: STATE_TURNING_OFF
11-24 11:24:04.165  4624  4624 D BluetoothMapService: MAP Service closeService in
11-24 11:24:04.165  4624  4624 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 11:24:04.165  4624  4624 D ObexServerSockets0: shutdown(block = true)
11-24 11:24:04.166  4624  4624 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 11:24:04.166  4624  4848 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-24 11:24:04.167  4624  4624 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 11:24:04.167  4624  4849 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-24 11:24:04.168  4624  4832 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-24 11:24:04.168  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:04.168  5556  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 11:24:04.168  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:24:04.168  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:24:04.168  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:24:04.168  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:24:04.168  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 11:24:04.168  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 11:24:04.168  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:24:04.168  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 11:24:04.169  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:04.169  5556  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 11:24:04.169  4624  4624 I BtOppRfcommListener: stopping Accept Thread
11-24 11:24:04.169  5556  5602 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 11:24:04.170  4624  5255 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 11:24:04.170  4624  5255 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 11:24:04.171   926  5324 D DhcpClient: Clearing IP address
,11-24 11:24:04.171   508   920 D CommandListener: Clearing all IP addresses on wlan0
11-24 11:24:04.174  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:24:04.179   508   920 D CommandListener: Setting iface cfg
11-24 11:24:04.179  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:24:04.180   926   939 I ActivityManager: Start proc 5624:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-24 11:24:04.180   926  5325 D DhcpClient: Receive thread stopped
,11-24 11:24:04.181  4624  4686 D BluetoothAdapterProperties: Scan Mode:20
11-24 11:24:04.181  4624  4682 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-24 11:24:04.182  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:24:04.184  4624  4624 D HeadsetService: Received stop request...Stopping profile...
11-24 11:24:04.186  4624  4624 D A2dpService: Received stop request...Stopping profile...
11-24 11:24:04.186  4624  4839 D A2dpStateMachine: Exit Disconnected: -1
11-24 11:24:04.186  3732  3755 D BluetoothHeadset: Proxy object disconnected
11-24 11:24:04.187  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:24:04.188  3106  3124 D BluetoothHeadset: Proxy object disconnected
11-24 11:24:04.189   926   926 D BluetoothHeadset: Proxy object disconnected
11-24 11:24:04.189   926   926 D BluetoothHeadset: Proxy object disconnected
11-24 11:24:04.189   926   926 D BluetoothHeadset: Proxy object disconnected
11-24 11:24:04.189   926   926 D BluetoothA2dp: Proxy object disconnected
11-24 11:24:04.189  4624  4624 D HidService: Received stop request...Stopping profile...
11-24 11:24:04.190  4624  4624 D HidService: Stopping Bluetooth HidService
,11-24 11:24:04.192  4624  4624 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:04.192  4624  4624 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:04.192  4624  4624 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:04.192  4624  4624 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:04.192  3553  5379 V NativeCrypto: Read error: ssl=0x7f8d3df200: I/O error during system call, Connection timed out
11-24 11:24:04.192  4624  4624 D HealthService: Received stop request...Stopping profile...
11-24 11:24:04.194   926  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 11:24:04.194   926  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-24 11:24:04.195  3553  5379 V NativeCrypto: SSL shutdown failed: ssl=0x7f8d3df200: I/O error during system call, Broken pipe
11-24 11:24:04.199   926   926 D RttService: SCAN_AVAILABLE : 1
11-24 11:24:04.200  3106  3106 D BluetoothA2dp: Proxy object disconnected
11-24 11:24:04.200  3106  3106 D HeadsetProfile: Bluetooth service disconnected
11-24 11:24:04.200   926  3038 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 11:24:04.200  3106  3106 D BluetoothInputDevice: Proxy object disconnected
11-24 11:24:04.200  3106  3106 D HidProfile: Bluetooth service disconnected
11-24 11:24:04.201  4624  4624 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 11:24:04.201  4624  4624 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 11:24:04.201   554   554 E Parcel  : Reading a NULL string not supported here.
,11-24 11:24:04.201  4624  4686 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 11:24:04.201  4624  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:04.201  4624  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:04.202  4624  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:04.202  4624  4686 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 11:24:04.203   926  2925 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-24 11:24:04.204  3695  3835 W QCNEJ   : |CORE| network lost: 100
,11-24 11:24:04.205  4624  4624 D PanService: Received stop request...Stopping profile...
11-24 11:24:04.206  3695  3835 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-24 11:24:04.207  4624  4624 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:04.207  4624  4624 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:04.208  4624  4624 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:04.208  4624  4624 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:04.208  4624  4624 D BluetoothMapService: Received stop request...Stopping profile...
11-24 11:24:04.208  4624  4624 D BluetoothMapService: stop()
11-24 11:24:04.209  4624  4624 D BluetoothMapAppObserver: deinitObservers()
11-24 11:24:04.209  4624  4624 D BluetoothMapAppObserver: removeReceiver()
,11-24 11:24:04.212  4624  4686 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 11:24:04.212  4624  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:04.212  4624  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:04.212  4624  4825 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 11:24:04.212  4624  4825 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 11:24:04.212  4624  4825 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 11:24:04.212  4624  4825 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 11:24:04.213  3106  3106 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 11:24:04.213  3106  3106 D PanProfile: Bluetooth service disconnected
11-24 11:24:04.214  4624  4624 D SapService: Received stop request...Stopping profile...
11-24 11:24:04.214  4624  4624 V SapService: stop()
11-24 11:24:04.215  4624  4624 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:04.215  4624  4624 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:04.215  4624  4624 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:04.215  4624  4624 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:04.214  3106  3106 D BluetoothMap: Proxy object disconnected
11-24 11:24:04.215  3106  3106 D MapProfile: Bluetooth service disconnected
11-24 11:24:04.215  4624  4624 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 11:24:04.215  4624  4624 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 11:24:04.215  4624  4686 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 11:24:04.215  4624  4624 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:04.216  4624  4624 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:04.216  4624  4624 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:04.216  4624  4624 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:04.216  4624  4624 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 11:24:04.216  4624  4686 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 11:24:04.216  4624  4624 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 11:24:04.216  4624  4624 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:04.216  4624  4624 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:04.216  4624  4624 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:04.216  4624  4624 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:04.217  4624  4624 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 11:24:04.217  4624  4624 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 11:24:04.217  4624  4624 D BluetoothMapService: MAP Service closeService in
11-24 11:24:04.217  4624  4624 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:04.217   926  2923 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 11:24:04.217  4624  4624 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:04.218  4624  4624 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:04.218  4624  4624 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:04.218  4624  4624 D BluetoothMapService: cleanup()
11-24 11:24:04.218  4624  4624 D BluetoothMapService: MAP Service closeService in
11-24 11:24:04.218  4624  4624 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:04.218  4624  4624 V BluetoothAdapterState: isTurningOn()=false
,11-24 11:24:04.219  4624  4624 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:04.219  4624  4624 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:04.219  4624  4682 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 11:24:04.219  4624  4682 D BluetoothAdapterProperties: Setting state to 15
11-24 11:24:04.219  4624  4682 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 11:24:04.219  4624  4682 I BluetoothAdapterState: Entering BleOnState
11-24 11:24:04.220  3106  3955 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 11:24:04.221  3106  3957 D BluetoothPan: onBluetoothStateChange on: false
11-24 11:24:04.222   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:24:04.222  3106  3118 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:24:04.222  3106  3955 D BluetoothPbap: onBluetoothStateChange: up=false
,11-24 11:24:04.223  3732  3962 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:24:04.223   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 11:24:04.223   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 11:24:04.224  3106  3124 D BluetoothMap: onBluetoothStateChange: up=false
11-24 11:24:04.224  3106  3957 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 11:24:04.225   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 11:24:04.225  4624  4682 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-24 11:24:04.225  4624  4682 D BluetoothAdapterProperties: Setting state to 16
11-24 11:24:04.225  4624  4682 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 11:24:04.226  4624  4682 D BluetoothAdapterProperties: onBleDisable
11-24 11:24:04.227  4624  4682 I BluetoothAdapterState: Entering PendingCommandState
11-24 11:24:04.227  4624  4683 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-24 11:24:04.228  4624  4686 D BluetoothAdapterProperties: Scan Mode:20
,11-24 11:24:04.228  4624  4825 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 11:24:04.229  4624  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:04.229   926  2923 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 11:24:04.232  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:04.232  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:24:04.232  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:24:04.232  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:24:04.232  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:24:04.232  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:24:04.232  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:24:04.232  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:24:04.232  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:24:04.232  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 11:24:04.233  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:04.233  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 11:24:04.235  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:24:04.251   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:24:04.252  5624  5624 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-24 11:24:04.266  3553  5644 I VacuumService: Vacuum at: now=1479983044266 tag=VacuumService
,11-24 11:24:04.272  5624  5624 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 11:24:04.274   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:24:04.274   508   920 D CommandListener: Clearing all IP addresses on wlan0
,11-24 11:24:04.275   508   920 D TetherController: Setting IP forward enable = 0
,11-24 11:24:04.276   926  2925 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-24 11:24:04.276   926  2925 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 11:24:04.277   926   943 D Tethering: MasterInitialState.processMessage what=3
11-24 11:24:04.278   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4e58b58:true
,11-24 11:24:04.279   926  2923 D DhcpClient: doQuit
,11-24 11:24:04.279   926  2923 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 11:24:04.280   926  5324 D DhcpClient: onQuitting
11-24 11:24:04.280  3415  3415 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 11:24:04.280  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:24:04.282  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 11:24:04.282  5210  5210 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e285efb and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-24 11:24:04.285  3942  3942 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-24 11:24:04.288  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:04.288  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:24:04.288  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:24:04.288  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:24:04.288  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 11:24:04.288  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:24:04.288  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:24:04.288  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:24:04.288  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:24:04.288  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 11:24:04.289  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:04.289  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 11:24:04.291  4997  5020 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 11:24:04.292  4997  5020 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 11:24:04.292  4997  5020 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 11:24:04.292  4997  5020 E SarControlService: no key has been found,reset the power
11-24 11:24:04.292  4997  5033 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 11:24:04.292  4997  5033 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-24 11:24:04.292  4997  5033 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 11:24:04.293  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:24:04.293  5022  5022 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 11:24:04.294  4997  5033 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 11:24:04.294  4997  5033 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 11:24:04.294  4997  5033 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 11:24:04.296  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:24:04.296  5022  5022 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 11:24:04.299  5022  5036 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3d4be79 HexData = [00000000ea03000000000000ffffffff]
11-24 11:24:04.299  5022  5036 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:24:04.299  5022  5036 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,11-24 11:24:04.301  3415  3415 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-24 11:24:04.303   926  3099 I ActivityManager: Start proc 5649:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-24 11:24:04.301  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 11:24:04.304  4997  5007 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 11:24:04.306  5022  5036 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3d4be79 HexData = [00000000eb03000000000000ffffffff]
11-24 11:24:04.307  5022  5036 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:24:04.307  5022  5036 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 11:24:04.308  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 11:24:04.308  4997  5008 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 11:24:04.309  3415  3415 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 11:24:04.320   508   920 E Netd    : netlink response contains error (No such file or directory)
,11-24 11:24:04.321   508   920 D TetherController: Setting IP forward enable = 0
,11-24 11:24:04.343  5649  5649 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-24 11:24:04.347  3415  3415 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 11:24:04.348  5624  5624 D LocalBluetoothProfileManager: Adding local MAP profile
,11-24 11:24:04.359  5624  5624 D BluetoothMap: Create BluetoothMap proxy object
,11-24 11:24:04.365  3415  3415 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 11:24:04.366  5624  5624 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 11:24:04.382  5624  5624 D DockEventReceiver: finishStartingService: stopping service
,11-24 11:24:04.387   926  3818 I ActivityManager: Killing 5102:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-24 11:24:04.472   926  2923 D wifi    : In wifi stop Hal
,11-24 11:24:04.472   926  2923 D wifi    : halHandle = 0x7f7b8e1dc0, mVM = 0x7f97ecd140, mCls = 0x100a02
11-24 11:24:04.472   926  3414 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 11:24:04.472   926  3414 D WifiHAL : Got a signal to exit!!!
11-24 11:24:04.472   926  3414 I WifiHAL : Exit wifi_event_loop
11-24 11:24:04.472  4969  4969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 11:24:04.474  4061  4194 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 11:24:04.474   926  2923 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 11:24:04.474   926  2923 E WifiHAL : Event processing terminated
,11-24 11:24:04.474   926  2923 D wifi    : In wifi cleaned up handler
11-24 11:24:04.474   926  2923 I WifiHAL : Internal cleanup completed
11-24 11:24:04.475  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:24:04.478  4624  4686 I bt_hci  : shut_down
,11-24 11:24:04.480  4624  4692 D bt_hwcfg: hw_epilog_process
,11-24 11:24:04.480  4624  4692 I bt_vendor: low_power_mode_cb
,11-24 11:24:04.485  4624  4692 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 11:24:04.485  4624  4692 I bt_vendor: epilog_cb
,11-24 11:24:04.485  4624  4692 I bt_hci  : epilog_finished_callback
,11-24 11:24:04.486  4624  4686 I bt_hci_h4: hal_close
,11-24 11:24:04.487  4624  4686 I bt_userial_vendor: device fd = 54 close
,11-24 11:24:04.495   926  3414 D wifi    : set interface wlan0 flags (DOWN)
,11-24 11:24:04.496   926  2923 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 11:24:04.588  5649  5649 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 11:24:04.588  5649  5649 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 11:24:04.588  5649  5649 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 11:24:04.588  5649  5649 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 11:24:04.588  5649  5649 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.k.d(PG:583)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 11:24:04.588  5649  5649 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
1,1-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 11:24:04.588  5649  5649 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 11:24:04.588  5649  5649 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 11:24:04.588  5649  5649 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 11:24:04.595  5624  5624 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 11:24:04.599  4624  4683 D bt_stack_manager: event_shut_down_stack finished.
11-24 11:24:04.599  4624  4682 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-24 11:24:04.601  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 11:24:04.602  4624  4682 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-24 11:24:04.602  4624  4624 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 11:24:04.602  4624  4624 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 11:24:04.602  4624  4624 D BtGatt.GattService: stop()
11-24 11:24:04.602  4624  4624 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 11:24:04.604  4624  4624 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:04.604  4624  4624 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:04.604  4624  4624 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:04.604  4624  4624 V BluetoothAdapterState: isBleTurningOff()=true
11-24 11:24:04.605  4624  4682 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 11:24:04.605  4624  4682 D BluetoothAdapterProperties: Setting state to 10
11-24 11:24:04.605  4624  4682 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 11:24:04.605  4624  4682 I BluetoothAdapterState: Entering OffState
11-24 11:24:04.606   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-24 11:24:04.614  4624  4624 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-24 11:24:04.614  4624  4624 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 11:24:04.614  4624  4624 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 11:24:04.615  4624  4683 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-24 11:24:04.617  5624  5624 D DockEventReceiver: finishStartingService: stopping service
11-24 11:24:04.620  3927  3927 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 11:24:04.626  3927  3927 D SystemUpdateService: onCreate
,11-24 11:24:04.629  3927  3927 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 11:24:04.632  4624  4624 I art     : System.exit called, status: 0
11-24 11:24:04.632  4624  4624 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-24 11:24:04.646  3927  3927 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-24 11:24:04.648  3927  5347 I iu.UploadsManager: num queued entries: 0
11-24 11:24:04.656  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-24 11:24:04.658  3927  3927 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 11:24:04.660  5352  5352 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-24 11:24:04.664  5352  5352 D SprintDMHelper: simOperator: 
11-24 11:24:04.664  5352  5352 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 11:24:04.676  4969  5689 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 11:24:04.678  3927  5347 I iu.UploadsManager: num updated entries: 0
11-24 11:24:04.678   926  3771 I ActivityManager: Process com.android.bluetooth (pid 4624) has died
,11-24 11:24:04.678  3927  5687 I SystemUpdateService: active receiver: enabled
,11-24 11:24:04.682  3927  5347 I iu.SyncManager: NEXT; no task
,11-24 11:24:04.694   926  3818 I ActivityManager: Start proc 5691:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 11:24:04.696  3927  5687 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 11:24:04.698   926   943 D Tethering: InitialState.processMessage what=4
,11-24 11:24:04.699  3927  5687 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 11:24:04.699  3927  5687 I SystemUpdateService: now status is 0 (complete)
11-24 11:24:04.699  3927  5687 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 11:24:04.699  3927  5687 I SystemUpdateService: file has been verified
11-24 11:24:04.699  3927  5687 I SystemUpdateService: OTA package size = 21989297
11-24 11:24:04.701   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 11:24:04.736  5691  5691 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 11:24:04.742  3927  5687 I SystemUpdateService: showing system update notification
,11-24 11:24:04.751   926  3812 I ActivityManager: Killing 5210:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 11:24:04.774   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 11:24:04.798  3927  3927 D SystemUpdateService: onDestroy
,11-24 11:24:04.802   926  3817 I ActivityManager: Killing 3852:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 11:24:04.929  5649  5673 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-24 11:24:04.939   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25c0715:true
,11-24 11:24:09.172   926   936 D WifiService: setWifiEnabled: true pid=5556, uid=10077
,11-24 11:24:09.172   926   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 11:24:09.180   508   920 D SoftapController: Softap fwReload - Ok
,11-24 11:24:09.184   508   920 D CommandListener: Setting iface cfg
,11-24 11:24:09.185   508   920 D CommandListener: Trying to bring down wlan0
,11-24 11:24:09.186   508   920 D CommandListener: Clearing all IP addresses on wlan0
,11-24 11:24:09.191   926  2923 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 11:24:09.775   926  2923 D wifi    : set interface wlan0 flags (UP)
,11-24 11:24:09.778   926  2923 I WifiHAL : Initializing wifi
11-24 11:24:09.778   926  2923 I WifiHAL : Creating socket
,11-24 11:24:09.782   926  2923 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-24 11:24:09.783   926  2923 D wifi    : Did set static halHandle = 0x7f7b8e1dc0
11-24 11:24:09.783   926  2923 D wifi    : halHandle = 0x7f7b8e1dc0, mVM = 0x7f97ecd140, mCls = 0x19a2
,11-24 11:24:09.783   926  2923 D wifi    : array field set
11-24 11:24:09.783   926  2923 I WifiNative-HAL: interface[0] = wlan0
11-24 11:24:09.784   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-24 11:24:09.787   926  5709 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547533757888
11-24 11:24:09.787   926  5709 D wifi    : waitForHalEvents called, vm = 0x7f97ecd140, obj = 0x19a2, env = 0x7f7c756140
,11-24 11:24:09.846  5710  5710 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 11:24:09.887   926  2923 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 11:24:09.895  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:24:09.897  5710  5710 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 11:24:09.926  5710  5710 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 11:24:09.926  5710  5710 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 11:24:09.936   926  2923 D WifiConfigStore: Loading config and enabling all networks 
,11-24 11:24:09.937  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:09.938  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:24:09.938  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:24:09.938  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:24:09.938  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:24:09.938  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:24:09.938  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:24:09.938  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:24:09.938  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:24:09.938  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 11:24:09.938  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 11:24:09.938  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 11:24:09.956   926  2923 D WifiConfigStore: loaded 0 passpoint configs
,11-24 11:24:09.956   926  2923 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 11:24:09.957   926  2923 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 11:24:09.957   926  2923 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-24 11:24:09.957   926  2923 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-24 11:24:09.958   926  2923 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-24 11:24:09.958   926  2923 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 11:24:09.958   926  2923 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 11:24:09.959   926  2923 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-24 11:24:09.959   926  2923 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 11:24:09.959   926  2923 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 11:24:09.959   926  2923 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-24 11:24:09.959   926  2923 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-24 11:24:09.961   926  2923 D WifiNative-HAL: Setting external_sim to 1
11-24 11:24:09.961   926  2923 D wifi    : setting dfs flag to true, 0x7f7c87d6c0
,11-24 11:24:09.961   926  2923 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 11:24:09.962   926  2923 D wifi    : setting scan oui 0x7f7c87d6c0
11-24 11:24:09.962   926  2923 D WifiHAL : Sending mac address OUI
,11-24 11:24:09.962  4969  4969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 11:24:09.965   926  2923 E native  : do suspend false
,11-24 11:24:09.971   926  2923 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 11:24:09.971   926   926 D RttService: SCAN_AVAILABLE : 3
11-24 11:24:09.971   926  3038 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 11:24:09.976   508   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 11:24:09.977   508   920 D CommandListener: Setting iface cfg
11-24 11:24:09.979   926  2922 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-24 11:24:09.979   926  2922 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 11:24:09.986   926  2922 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 11:24:09.987   926  2922 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 11:24:09.992   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=212510 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-24 11:24:13.021  5710  5710 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 11:24:13.026  5710  5710 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 11:24:13.076   926  2923 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 11:24:13.077   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 11:24:13.077   926  2923 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:24:13.089   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 11:24:13.124   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 11:24:13.131  5710  5710 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 11:24:13.562  5710  5710 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 11:24:13.598  5710  5710 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 11:24:13.599  5710  5710 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 11:24:13.608   926  2923 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 11:24:13.608   926  2923 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:24:13.609   926  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 11:24:13.626   926  2923 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:24:13.640   508   920 D CommandListener: Setting iface cfg
,11-24 11:24:13.646   926  2923 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 11:24:13.653   926  5716 D DhcpClient: Receive thread started
,11-24 11:24:13.657   926  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 11:24:13.657   926  2923 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 11:24:13.657   926  2925 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 11:24:13.739   926  2923 E native  : do suspend false
,11-24 11:24:13.756   926  5715 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 11:24:13.805   926  5716 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172625, domain null
,11-24 11:24:13.806   926  5715 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172625 seconds
,11-24 11:24:13.808   926  5715 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 11:24:13.867   926  5716 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 11:24:13.867   926  5715 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 11:24:13.872   508   920 D CommandListener: Setting iface cfg
,11-24 11:24:13.876   926  2923 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 11:24:13.882   926  5715 D DhcpClient: Scheduling renewal in 86399s
,11-24 11:24:13.891   926  2923 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 11:24:13.893   926  2923 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 11:24:13.894   926  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-24 11:24:13.896   926  2925 D ConnectivityService: Adding iface wlan0 to network 101
11-24 11:24:13.909   926  2923 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 11:24:13.948   926  2925 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-24 11:24:13.949   926  2925 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-24 11:24:13.954   926  2925 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 11:24:13.958   926  2925 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-24 11:24:13.960   926  2925 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 11:24:13.967   926  2925 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 11:24:13.972   926  2925 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 11:24:13.972   926  2925 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 11:24:13.972   926  2925 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 11:24:13.972   926  2925 D ConnectivityService:    accepting network in place of null
11-24 11:24:13.972   926  2923 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 11:24:13.972   926  2923 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 11:24:13.973   926  2925 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 11:24:13.997   926  5714 D NetlinkSocketObserver: NeighborEvent{elapsedMs=216515, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 11:24:13.998   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:24:14.019   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:24:14.022   926  2925 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 11:24:14.022   926  2925 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 11:24:14.022  3695  3835 W QCNEJ   : |CORE| network available: 101
11-24 11:24:14.024   926  2925 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-24 11:24:14.024   926   943 D Tethering: MasterInitialState.processMessage what=3
11-24 11:24:14.028  3695  3835 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 11:24:14.028  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:14.028  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:24:14.028  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:24:14.028  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:24:14.028  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:24:14.028  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:24:14.028  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 11:24:14.028  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 11:24:14.028  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:24:14.028  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 11:24:14.028  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:14.029  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 11:24:14.030  3695  3835 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-24 11:24:14.030  3695  3835 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 11:24:14.038  4997  5020 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 11:24:14.038  4997  5020 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-24 11:24:14.038  4997  5020 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 11:24:14.038  4997  5020 E SarControlService: no key has been found,reset the power
11-24 11:24:14.039  4997  5033 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 11:24:14.039  4997  5033 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 11:24:14.039  4997  5033 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 11:24:14.039  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:24:14.039  5022  5022 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 11:24:14.041  4997  5033 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 11:24:14.041  4997  5033 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 11:24:14.041  4997  5033 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-24 11:24:14.043  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-24 11:24:14.043  5022  5022 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 11:24:14.044  3942  3942 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-24 11:24:14.047  3927  3927 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 11:24:14.048  5022  5036 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3d4be79 HexData = [00000000ec03000000000000ffffffff]
11-24 11:24:14.048  5022  5036 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:24:14.048  5022  5036 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-24 11:24:14.050  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 11:24:14.051  4997  5007 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 11:24:14.051  5022  5036 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3d4be79 HexData = [00000000ed03000000000000ffffffff]
11-24 11:24:14.051  5022  5036 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:24:14.051  5022  5036 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-24 11:24:14.052  3927  3927 D SystemUpdateService: onCreate
11-24 11:24:14.054  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 11:24:14.054  4997  5008 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 11:24:14.057  3927  3927 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 11:24:14.068  3927  3927 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 11:24:14.074  3927  5726 I SystemUpdateService: active receiver: enabled
,11-24 11:24:14.077  3927  5347 I iu.UploadsManager: num queued entries: 0
,11-24 11:24:14.078  3927  5347 I iu.UploadsManager: num updated entries: 0
,11-24 11:24:14.081   926  5713 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 11:24:14.086  3927  5726 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 11:24:14.088  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 11:24:14.091  3927  3927 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 11:24:14.093  5352  5352 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 11:24:14.096  5352  5352 D SprintDMHelper: simOperator: 
11-24 11:24:14.097  5352  5352 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 11:24:14.107  3927  5347 I iu.SyncManager: NEXT; no task
,11-24 11:24:14.108  3927  5726 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-24 11:24:14.108  3927  5726 I SystemUpdateService: now status is 0 (complete)
,11-24 11:24:14.115  3927  5726 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-24 11:24:14.115  3927  5726 I SystemUpdateService: file has been verified
11-24 11:24:14.115  3927  5726 I SystemUpdateService: OTA package size = 21989297
,11-24 11:24:14.132  3927  5726 I SystemUpdateService: showing system update notification
,11-24 11:24:14.140   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 11:24:14.141  3927  3927 D SystemUpdateService: onDestroy
,11-24 11:24:14.176   926   936 D WifiService: setWifiEnabled: false pid=5556, uid=10077
,11-24 11:24:14.176   926   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-24 11:24:14.178   926  2923 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 11:24:14.178   926  2923 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 11:24:14.178   926  2923 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 11:24:14.178   926  2923 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 11:24:14.179   926  5713 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 10:24:14 GMT], X-Android-Received-Millis=[1479983054178], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479983054125]}
11-24 11:24:14.179   926  2925 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 11:24:14.179   926  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-24 11:24:14.179   926  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 11:24:14.182   926  2925 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 11:24:14.187   926  5715 D DhcpClient: Clearing IP address
,11-24 11:24:14.188   508   920 D CommandListener: Clearing all IP addresses on wlan0
11-24 11:24:14.189   508   920 D CommandListener: Setting iface cfg
,11-24 11:24:14.191   926  5716 D DhcpClient: Receive thread stopped
,11-24 11:24:14.192  3553  5727 V NativeCrypto: SSL handshake aborted: ssl=0x7f7d894700: I/O error during system call, Connection timed out
,11-24 11:24:14.199   926   937 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-24 11:24:14.200   926  5713 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-24 11:24:14.201   926  5713 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 11:24:14.201   926  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-24 11:24:14.201   926  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-24 11:24:14.204   554   554 E Parcel  : Reading a NULL string not supported here.
,11-24 11:24:14.206  4969  5731 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
11-24 11:24:14.206   926   926 D RttService: SCAN_AVAILABLE : 1
,11-24 11:24:14.206   926  3038 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 11:24:14.208   926  2925 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-24 11:24:14.209  3695  3835 W QCNEJ   : |CORE| network lost: 101
11-24 11:24:14.210  3695  3835 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 11:24:14.212   926  2923 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-24 11:24:14.214   926  5713 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-24 11:24:14.215   926  2923 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/216.58.214.238 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
11-24 11:24:14.217  4969  ,5731 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:223)
11-24 11:24:14.217  4969  5731 W Babel_NetworkConnectionCheckingService: 	... 23 more
11-24 11:24:14.217  4969  5731 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 11:24:14.232   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:24:14.253   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:24:14.254   926  2925 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-24 11:24:14.254   508   920 D CommandListener: Clearing all IP addresses on wlan0
11-24 11:24:14.254   926  2925 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 11:24:14.255   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-24 11:24:14.258  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:14.258  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:24:14.258  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:24:14.258  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:24:14.258  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:24:14.258  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:24:14.258  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:24:14.258  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:24:14.258  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:24:14.258  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 11:24:14.258  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:14.258  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 11:24:14.259  3942  3942 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-24 11:24:14.263  3927  3927 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 11:24:14.265  4997  5020 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 11:24:14.265  4997  5020 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 11:24:14.265  4997  5020 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 11:24:14.266  4997  5020 E SarControlService: no key has been found,reset the power
11-24 11:24:14.266  4997  5033 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 11:24:14.266  4997  5033 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 11:24:14.266  4997  5033 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 11:24:14.266  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:24:14.266  5022  5022 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 11:24:14.268  4997  5033 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 11:24:14.268  4997  5033 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 11:24:14.268  4997  5033 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 11:24:14.269  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-24 11:24:14.269  5022  5022 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 11:24:14.272  3927  3927 D SystemUpdateService: onCreate
11-24 11:24:14.274  5022  5036 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3d4be79 HexData = [00000000ee03000000000000ffffffff]
11-24 11:24:14.274  5022  5036 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-24 11:24:14.274  5022  5036 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-24 11:24:14.275  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 11:24:14.275  4997  5008 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 11:24:14.277  5022  5036 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3d4be79 HexData = [00000000ef03000000000000ffffffff]
11-24 11:24:14.277  5022  5036 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:24:14.277  5022  5036 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-24 11:24:14.278  5022  5022 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 11:24:14.278  4997  5007 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 11:24:14.279  3927  3927 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 11:24:14.283  3927  5744 I SystemUpdateService: active receiver: enabled
,11-24 11:24:14.287  3927  3927 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 11:24:14.292  3927  5347 I iu.UploadsManager: num queued entries: 0
,11-24 11:24:14.292  3927  5347 I iu.UploadsManager: num updated entries: 0
11-24 11:24:14.293  3927  5347 I iu.SyncManager: NEXT; no task
,11-24 11:24:14.295  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 11:24:14.297  3927  3927 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 11:24:14.299  5352  5352 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 11:24:14.302  5352  5352 D SprintDMHelper: simOperator: 
11-24 11:24:14.302  5352  5352 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 11:24:14.305   508   920 E Netd    : netlink response contains error (No such file or directory)
,11-24 11:24:14.306   926  2925 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-24 11:24:14.306   926  2925 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 11:24:14.309   926  2923 D DhcpClient: doQuit
,11-24 11:24:14.309   926  2923 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 11:24:14.310  5710  5710 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 11:24:14.310   926  5715 D DhcpClient: onQuitting
11-24 11:24:14.310  3927  5744 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 11:24:14.313  4969  5748 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 11:24:14.313  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:14.313  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:24:14.313  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:24:14.313  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:24:14.313  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 11:24:14.313  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:24:14.313  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:24:14.313  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:24:14.313  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:24:14.313  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 11:24:14.313  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:14.313  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 11:24:14.319  3927  5744 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 11:24:14.319  3927  5744 I SystemUpdateService: now status is 0 (complete)
11-24 11:24:14.319  3927  5744 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 11:24:14.319  3927  5744 I SystemUpdateService: file has been verified
11-24 11:24:14.319  3927  5744 I SystemUpdateService: OTA package size = 21989297
,11-24 11:24:14.324  5710  5710 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 11:24:14.327  5710  5710 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 11:24:14.337  3927  5744 I SystemUpdateService: showing system update notification
,11-24 11:24:14.343   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 11:24:14.344  3927  3927 D SystemUpdateService: onDestroy
,11-24 11:24:14.357  5710  5710 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 11:24:14.362  5710  5710 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 11:24:14.465   926  2923 D wifi    : In wifi stop Hal
,11-24 11:24:14.465   926  2923 D wifi    : halHandle = 0x7f7b8e1dc0, mVM = 0x7f97ecd140, mCls = 0x19a2
11-24 11:24:14.468   926  5709 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 11:24:14.468   926  5709 D WifiHAL : Got a signal to exit!!!
11-24 11:24:14.468   926  5709 I WifiHAL : Exit wifi_event_loop
,11-24 11:24:14.469   926  2923 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 11:24:14.470   926  2923 E WifiHAL : Event processing terminated
11-24 11:24:14.469  4969  4969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 11:24:14.470   926  2923 D wifi    : In wifi cleaned up handler
11-24 11:24:14.470   926  2923 I WifiHAL : Internal cleanup completed
11-24 11:24:14.473  4061  4194 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 11:24:14.475  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:24:14.493   926  5709 D wifi    : set interface wlan0 flags (DOWN)
,11-24 11:24:14.494   926  2923 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 11:24:14.700   926   943 D Tethering: InitialState.processMessage what=4
,11-24 11:24:14.707   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 11:24:15.023   926  2925 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 11:24:16.563   556   556 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 11:24:16.564   556   556 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 11:24:19.215   926   943 I ActivityManager: Start proc 5750:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 11:24:19.311  5750  5750 D AdapterServiceConfig: Adding HeadsetService
,11-24 11:24:19.312  5750  5750 D AdapterServiceConfig: Adding A2dpService
11-24 11:24:19.312  5750  5750 D AdapterServiceConfig: Adding HidService
11-24 11:24:19.312  5750  5750 D AdapterServiceConfig: Adding HealthService
11-24 11:24:19.312  5750  5750 D AdapterServiceConfig: Adding PanService
11-24 11:24:19.312  5750  5750 D AdapterServiceConfig: Adding GattService
11-24 11:24:19.312  5750  5750 D AdapterServiceConfig: Adding BluetoothMapService
11-24 11:24:19.313  5750  5750 D AdapterServiceConfig: Adding SapService
,11-24 11:24:19.326   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3436090:true
,11-24 11:24:19.326  5750  5750 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 11:24:19.330  5750  5750 I bt_bluedroid: init
,11-24 11:24:19.330  5750  5762 I BluetoothAdapterState: Entering OffState
,11-24 11:24:19.333  5750  5763 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-24 11:24:19.333  5750  5763 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 11:24:19.333  5750  5763 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 11:24:19.333  5750  5763 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-24 11:24:19.334  5750  5750 I bt_bluedroid: get_profile_interface socket
,11-24 11:24:19.335  5750  5766 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-24 11:24:19.335  5750  5750 I bt_bluedroid: get_profile_interface sdp
,11-24 11:24:19.336  5750  5766 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 11:24:19.339  5750  5761 I bt_bluedroid: config_hci_snoop_log
,11-24 11:24:19.340   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 11:24:19.344  5750  5762 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 11:24:19.345  5750  5762 D BluetoothAdapterProperties: Setting state to 14
11-24 11:24:19.345  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 11:24:19.346  5750  5762 D BluetoothBondStateMachine: make
,11-24 11:24:19.347  5750  5767 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 11:24:19.350  5750  5762 I BluetoothAdapterState: Entering PendingCommandState
,11-24 11:24:19.351  5750  5750 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 11:24:19.353  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
,11-24 11:24:19.353  5750  5750 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 11:24:19.354  5750  5750 D BtGatt.GattService: Received start request. Starting profile...
11-24 11:24:19.354  5750  5750 D BtGatt.GattService: start()
11-24 11:24:19.354  5750  5750 I bt_bluedroid: get_profile_interface gatt
11-24 11:24:19.355  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
11-24 11:24:19.355  5750  5750 D BtGatt.AdvertiseManager: advertise manager created
,11-24 11:24:19.359  5750  5750 V BluetoothAdapterState: isTurningOff()=false
,11-24 11:24:19.359  5750  5750 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:19.359  5750  5750 V BluetoothAdapterState: isBleTurningOn()=true
11-24 11:24:19.359  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:19.360  5750  5762 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 11:24:19.361  5750  5762 I bt_bluedroid: bt_bluedroid
11-24 11:24:19.361  5750  5763 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 11:24:19.361  5750  5763 I bt_hci  : start_up
,11-24 11:24:19.366  5750  5763 I bt_vendor: alloc value 0xf42b7871
11-24 11:24:19.366  5750  5763 I bt_vendor: init
11-24 11:24:19.366  5750  5763 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 11:24:19.366  5750  5763 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 11:24:19.475  5750  5763 D bt_hci  : start_up starting async portion
,11-24 11:24:19.476  5750  5770 I bt_hci  : event_finish_startup
11-24 11:24:19.476  5750  5770 I bt_hci_h4: hal_open
11-24 11:24:19.476  5750  5770 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-24 11:24:19.473  5771  5771 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-24 11:24:19.479  5750  5770 I bt_userial_vendor: device fd = 54 open
,11-24 11:24:19.495  5750  5770 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 11:24:19.497  5750  5770 D bt_hwcfg: Chipset BCM4358A3
,11-24 11:24:19.498  5750  5770 D bt_hwcfg: Target name = [BCM4358A3]
11-24 11:24:19.498  5750  5770 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 11:24:19.902  5750  5770 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 11:24:19.902  5750  5770 D bt_hwcfg: Settlement delay -- 100 ms
,11-24 11:24:19.902  5750  5770 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 11:24:20.036  5750  5770 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 11:24:20.036  5750  5770 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-24 11:24:20.038  5750  5770 I bt_hwcfg: vendor lib fwcfg completed
,11-24 11:24:20.038  5750  5770 I bt_vendor: firmware callback
,11-24 11:24:20.038  5750  5770 I bt_hci  : firmware_config_callback
,11-24 11:24:20.048  5750  5773 I bt_btu  : btu_task pending for preload complete event
,11-24 11:24:20.048  5750  5773 I bt_btu_task: Bluetooth chip preload is complete
11-24 11:24:20.048  5750  5773 I bt_btu  : btu_task received preload complete event
,11-24 11:24:20.053  5750  5773 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 11:24:20.053  5750  5773 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 11:24:20.053  5750  5773 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 11:24:20.054  5750  5773 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 11:24:20.054  5750  5773 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-24 11:24:20.054  5750  5773 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 11:24:20.054  5750  5773 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 11:24:20.054  5750  5773 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 11:24:20.054  5750  5773 I         : BTE_InitTraceLevels -- TRC_GAP
,11-24 11:24:20.054  5750  5773 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 11:24:20.054  5750  5773 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 11:24:20.055  5750  5773 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 11:24:20.055  5750  5773 I         : BTE_InitTraceLevels -- TRC_SMP
,11-24 11:24:20.055  5750  5773 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 11:24:20.055  5750  5773 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 11:24:20.135  5750  5773 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4235549
11-24 11:24:20.135  5750  5773 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4235549 
,11-24 11:24:20.157  5750  5766 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 11:24:20.158  5750  5766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 11:24:20.159  5750  5766 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 11:24:20.161  5750  5766 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 11:24:20.164  5750  5766 D BluetoothAdapterProperties: Scan Mode:20
,11-24 11:24:20.164  5750  5766 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 11:24:20.164  5750  5766 D bt_hci  : do_postload posting postload work item
11-24 11:24:20.165  5750  5770 I bt_hci  : event_postload
11-24 11:24:20.165  5750  5770 I bt_vendor: sco_config_cb
11-24 11:24:20.165  5750  5770 I bt_hci  : sco_config_callback postload finished.
,11-24 11:24:20.168  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:24:20.170  5750  5766 D bt_bte_conf: Device ID record 1 : primary
11-24 11:24:20.170  5750  5766 D bt_bte_conf:   vendorId            = 000f
11-24 11:24:20.170  5750  5766 D bt_bte_conf:   vendorIdSource      = 0001
11-24 11:24:20.170  5750  5766 D bt_bte_conf:   product             = 1200
11-24 11:24:20.170  5750  5766 D bt_bte_conf:   version             = 1436
11-24 11:24:20.170  5750  5766 D bt_bte_conf:   clientExecutableURL = 
11-24 11:24:20.170  5750  5766 D bt_bte_conf:   serviceDescription  = 
11-24 11:24:20.170  5750  5766 D bt_bte_conf:   documentationURL    = 
11-24 11:24:20.171  5750  5766 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-24 11:24:20.171  5750  5770 I bt_vendor: low_power_mode_cb
,11-24 11:24:20.171  5750  5763 D bt_stack_manager: event_start_up_stack finished
,11-24 11:24:20.172  5750  5762 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 11:24:20.172  5750  5762 D BluetoothAdapterProperties: Setting state to 15
11-24 11:24:20.172  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 11:24:20.174  5750  5762 I BluetoothAdapterState: Entering BleOnState
,11-24 11:24:20.179  5750  5762 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-24 11:24:20.179  5750  5762 D BluetoothAdapterProperties: Setting state to 11
11-24 11:24:20.179  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 11:24:20.184  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:24:20.186  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
,11-24 11:24:20.187  5750  5750 D HeadsetService: Received start request. Starting profile...
11-24 11:24:20.190  5750  5750 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 11:24:20.190  5750  5750 D HeadsetStateMachine: make
,11-24 11:24:20.194  5750  5762 I BluetoothAdapterState: Entering PendingCommandState
,11-24 11:24:20.198  5750  5750 D HeadsetStateMachine: max_hf_connections = 1
,11-24 11:24:20.199  5750  5750 I bt_bluedroid: get_profile_interface handsfree
11-24 11:24:20.199  5750  5766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 11:24:20.200  5750  5766 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-24 11:24:20.202  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
,11-24 11:24:20.203  5750  5750 D A2dpService: Received start request. Starting profile...
11-24 11:24:20.204  5750  5750 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 11:24:20.204  5750  5750 I bt_bluedroid: get_profile_interface avrcp
,11-24 11:24:20.210  5750  5750 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 11:24:20.210  5750  5750 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 11:24:20.210  5750  5750 D A2dpStateMachine: make
11-24 11:24:20.211  5750  5750 I bt_bluedroid: get_profile_interface a2dp
,11-24 11:24:20.211  5750  5766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 11:24:20.212  5750  5781 D A2dpStateMachine: Enter Disconnected: -2
,11-24 11:24:20.214  5750  5750 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 11:24:20.214  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
,11-24 11:24:20.215  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 11:24:20.216  5624  5624 D BluetoothInputDevice: Proxy object connected
11-24 11:24:20.217  5750  5750 D HidService: Received start request. Starting profile...
11-24 11:24:20.217  5750  5750 I bt_bluedroid: get_profile_interface hidhost
11-24 11:24:20.217  5750  5766 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf421656d
11-24 11:24:20.217  5750  5750 D HidService: setHidService(): set to: null
11-24 11:24:20.217  5750  5766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 11:24:20.218  5624  5624 D HidProfile: Bluetooth service connected
11-24 11:24:20.218  5750  5750 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 11:24:20.218  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
11-24 11:24:20.219  5750  5750 D HealthService: Received start request. Starting profile...
11-24 11:24:20.220  5750  5750 I bt_bluedroid: get_profile_interface health
,11-24 11:24:20.221  5750  5750 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 11:24:20.222  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
,11-24 11:24:20.223  5750  5750 D PanService: Received start request. Starting profile...
,11-24 11:24:20.223  5624  5624 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 11:24:20.223  5750  5750 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 11:24:20.223  5750  5750 I bt_bluedroid: get_profile_interface pan
11-24 11:24:20.223  5750  5766 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 11:24:20.223  5624  5624 D PanProfile: Bluetooth service connected
,11-24 11:24:20.225  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
,11-24 11:24:20.228  5750  5750 D BluetoothMapService: Received start request. Starting profile...
,11-24 11:24:20.228  5750  5750 D BluetoothMapService: start()
11-24 11:24:20.230  5750  5750 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-24 11:24:20.231  5750  5750 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 11:24:20.231  5750  5750 D BluetoothMapAppObserver: createReceiver()
11-24 11:24:20.232  5750  5750 D BluetoothMapAppObserver: initObservers()
11-24 11:24:20.232  5750  5750 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 11:24:20.235  5624  5624 D BluetoothMap: Proxy object connected
,11-24 11:24:20.235  5624  5624 D MapProfile: Bluetooth service connected
11-24 11:24:20.236  5624  5624 D BluetoothMap: getConnectedDevices()
11-24 11:24:20.236  5624  5624 D BluetoothMap: Bluetooth is Not enabled
,11-24 11:24:20.239  5750  5750 V SapService: SapBinder()
,11-24 11:24:20.239  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
,11-24 11:24:20.239  5750  5750 D SapService: Received start request. Starting profile...
11-24 11:24:20.239  5750  5750 V SapService: start()
,11-24 11:24:20.242  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:20.242  5750  5750 V BluetoothAdapterState: isTurningOn()=true
,11-24 11:24:20.242  5750  5779 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 11:24:20.242  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:20.242  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:20.242  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:20.242  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-24 11:24:20.242  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:20.243  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:20.244  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:20.244  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-24 11:24:20.244  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:20.244  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:20.244  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:20.244  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-24 11:24:20.244  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:20.244  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:20.245  5750  5762 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 11:24:20.245  5750  5762 D BluetoothAdapterProperties: ScanMode =  20
11-24 11:24:20.245  5750  5762 D BluetoothAdapterProperties: State =  11
11-24 11:24:20.245  5750  5762 D BluetoothAdapterProperties: Setting state to 12
11-24 11:24:20.245  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 11:24:20.246  5750  5762 I BluetoothAdapterState: Entering OnState
11-24 11:24:20.246  3106  3957 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 11:24:20.246  5750  5766 D BluetoothAdapterProperties: Scan Mode:21
11-24 11:24:20.246  5750  5766 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 11:24:20.247  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-24 11:24:20.249  3106  3124 D BluetoothPan: onBluetoothStateChange on: true
11-24 11:24:20.250  3106  3106 D BluetoothA2dp: Proxy object connected
11-24 11:24:20.251   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:24:20.251  3106  3957 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:24:20.252  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:24:20.252  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:24:20.252  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:24:20.252  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 11:24:20.252  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:24:20.252  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:24:20.252  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:24:20.252  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:24:20.252  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 11:24:20.252  3106  3955 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 11:24:20.252  3106  3106 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 11:24:20.252  3106  3106 D PanProfile: Bluetooth service connected
11-24 11:24:20.253  3732  3962 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:24:20.254  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 11:24:20.254   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 11:24:20.254   926   926 D BluetoothA2dp: Proxy object connected
11-24 11:24:20.255  5624  5636 D BluetoothPan: onBluetoothStateChange on: true
,11-24 11:24:20.255  5624  5634 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 11:24:20.255   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:24:20.256  5624  5636 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 11:24:20.257  3106  3124 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 11:24:20.258  5750  5750 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 11:24:20.259  3106  3118 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 11:24:20.259  3106  3106 D BluetoothMap: Proxy object connected
11-24 11:24:20.259  3106  3106 D MapProfile: Bluetooth service connected
11-24 11:24:20.259  3106  3106 D BluetoothMap: getConnectedDevices()
11-24 11:24:20.259  5750  5750 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 11:24:20.260  5750  5750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:24:20.261  5624  5634 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 11:24:20.261   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:24:20.261  3106  3106 D BluetoothInputDevice: Proxy object connected
,11-24 11:24:20.261  3106  3106 D HidProfile: Bluetooth service connected
11-24 11:24:20.262   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
,11-24 11:24:20.263  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-24 11:24:20.264  5750  5750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:24:20.265  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:24:20.266  5750  5750 D ObexServerSockets: Succeed to create listening sockets 
11-24 11:24:20.266  5750  5750 D ObexServerSockets0: startAccept()
11-24 11:24:20.266  5750  5750 D ObexServerSockets0: prepareForNewConnect()
11-24 11:24:20.266  5624  5624 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-24 11:24:20.268  5750  5750 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 11:24:20.268  5750  5750 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 11:24:20.268  5750  5787 D ObexServerSockets0: Accepting socket connection...
11-24 11:24:20.268  5750  5750 D BluetoothMapService: onReceive
11-24 11:24:20.268  5750  5750 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 11:24:20.268  5750  5750 D BluetoothMapService: STATE_ON
,11-24 11:24:20.270  5750  5788 D ObexServerSockets0: Accepting socket connection...
,11-24 11:24:20.271  5624  5624 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-24 11:24:20.271  5750  5789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:24:20.273  5750  5789 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 11:24:20.273  5750  5789 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 11:24:20.279  5624  5624 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 11:24:20.281  5624  5624 D BluetoothA2dp: Proxy object connected
,11-24 11:24:20.285  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 11:24:20.286  5624  5624 D DockEventReceiver: finishStartingService: stopping service
,11-24 11:24:20.292  3106  3106 D BluetoothPbap: Proxy object connected
,11-24 11:24:20.292  3106  3106 D PbapServerProfile: Bluetooth service connected
,11-24 11:24:20.293  5624  5624 D BluetoothPbap: Proxy object connected
11-24 11:24:20.293  5624  5624 D PbapServerProfile: Bluetooth service connected
,11-24 11:24:20.299  5750  5750 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 11:24:20.299  5750  5750 D ObexServerSockets0: prepareForNewConnect()
11-24 11:24:20.301  5750  5793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 11:24:20.315  5750  5797 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 11:24:20.317  5750  5797 I BtOppRfcommListener: Accept thread started.
,11-24 11:24:20.353  3732  3760 D BluetoothHeadset: Proxy object connected
,11-24 11:24:20.353  3106  3124 D BluetoothHeadset: Proxy object connected
11-24 11:24:20.354  3106  3106 D HeadsetProfile: Bluetooth service connected
11-24 11:24:20.354   926   926 D BluetoothHeadset: Proxy object connected
,11-24 11:24:20.354   926   926 D BluetoothHeadset: Proxy object connected
11-24 11:24:20.354   926   926 D BluetoothHeadset: Proxy object connected
11-24 11:24:20.354  3732  3755 D BluetoothHeadset: Proxy object connected
11-24 11:24:20.356   926   943 D BluetoothHeadset: Proxy object connected
,11-24 11:24:20.361   926   943 D BluetoothHeadset: Proxy object connected
,11-24 11:24:20.375  5624  5634 D BluetoothHeadset: Proxy object connected
,11-24 11:24:20.377  5624  5624 D HeadsetProfile: Bluetooth service connected
,11-24 11:24:21.979   926  2925 D ConnectivityService: handlePromptUnvalidated 101
,11-24 11:24:22.589  3639  3804 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-24 11:24:22.589  3639  3804 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-24 11:24:22.618  3553  3553 I ConfigService: onCreate
,11-24 11:24:24.193  5750  5762 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 11:24:24.193  5750  5762 D BluetoothAdapterProperties: Setting state to 13
11-24 11:24:24.193  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-24 11:24:24.195  5750  5762 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 11:24:24.198  5750  5762 I BluetoothAdapterState: Entering PendingCommandState
,11-24 11:24:24.200  5750  5750 D BluetoothMapService: onReceive
11-24 11:24:24.200  5750  5750 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-24 11:24:24.200  5750  5750 D BluetoothMapService: STATE_TURNING_OFF
,11-24 11:24:24.201  5750  5750 D BluetoothMapService: MAP Service closeService in
11-24 11:24:24.201  5750  5750 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 11:24:24.201  5750  5750 D ObexServerSockets0: shutdown(block = true)
,11-24 11:24:24.203  5750  5750 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 11:24:24.203  5750  5787 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 11:24:24.203  5750  5775 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 11:24:24.203  5750  5750 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 11:24:24.203  5750  5788 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 11:24:24.208  5750  5750 I BtOppRfcommListener: stopping Accept Thread
11-24 11:24:24.209  5750  5797 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 11:24:24.209  5750  5797 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 11:24:24.210  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:24.210  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:24:24.210  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:24:24.210  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:24:24.210  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 11:24:24.210  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:24:24.210  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:24:24.210  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:24:24.210  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:24:24.210  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 11:24:24.212  5750  5766 D BluetoothAdapterProperties: Scan Mode:20
11-24 11:24:24.213  5750  5762 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 11:24:24.212  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:24:24.213  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 11:24:24.216  5624  5624 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 11:24:24.218  5750  5750 D HeadsetService: Received stop request...Stopping profile...
11-24 11:24:24.220  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:24:24.225  3732  3962 D BluetoothHeadset: Proxy object disconnected
,11-24 11:24:24.225  3106  3124 D BluetoothHeadset: Proxy object disconnected
11-24 11:24:24.226  5624  5634 D BluetoothHeadset: Proxy object disconnected
11-24 11:24:24.226   926   926 D BluetoothHeadset: Proxy object disconnected
11-24 11:24:24.226   926   926 D BluetoothHeadset: Proxy object disconnected
11-24 11:24:24.226   926   926 D BluetoothHeadset: Proxy object disconnected
,11-24 11:24:24.230  5624  5624 D DockEventReceiver: finishStartingService: stopping service
11-24 11:24:24.230  3106  3106 D HeadsetProfile: Bluetooth service disconnected
,11-24 11:24:24.232  5750  5750 D A2dpService: Received stop request...Stopping profile...
11-24 11:24:24.232  5624  5624 D HeadsetProfile: Bluetooth service disconnected
11-24 11:24:24.234  5750  5781 D A2dpStateMachine: Exit Disconnected: -1
,11-24 11:24:24.234   926   926 D BluetoothA2dp: Proxy object disconnected
11-24 11:24:24.235  5624  5624 D BluetoothA2dp: Proxy object disconnected
11-24 11:24:24.236  5750  5750 D HidService: Received stop request...Stopping profile...
11-24 11:24:24.236  5750  5750 D HidService: Stopping Bluetooth HidService
11-24 11:24:24.235  3106  3106 D BluetoothA2dp: Proxy object disconnected
,11-24 11:24:24.237  3106  3106 D BluetoothInputDevice: Proxy object disconnected
11-24 11:24:24.238  3106  3106 D HidProfile: Bluetooth service disconnected
11-24 11:24:24.238  5624  5624 D BluetoothInputDevice: Proxy object disconnected
11-24 11:24:24.238  5624  5624 D HidProfile: Bluetooth service disconnected
11-24 11:24:24.239  5750  5750 D HealthService: Received stop request...Stopping profile...
,11-24 11:24:24.241  5750  5750 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:24.241  5750  5750 V BluetoothAdapterState: isTurningOn()=false
,11-24 11:24:24.242  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:24.242  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:24.242  5750  5750 D PanService: Received stop request...Stopping profile...
11-24 11:24:24.243  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 11:24:24.243  5624  5624 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 11:24:24.244  3106  3106 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-24 11:24:24.244  5624  5624 D PanProfile: Bluetooth service disconnected
11-24 11:24:24.244  3106  3106 D PanProfile: Bluetooth service disconnected
,11-24 11:24:24.246  5750  5750 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-24 11:24:24.246  5750  5750 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 11:24:24.246  5750  5773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:24.246  5750  5773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:24.246  5750  5773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:24.246  5750  5766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 11:24:24.246  5750  5766 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 11:24:24.246  5750  5750 D BluetoothMapService: Received stop request...Stopping profile...
11-24 11:24:24.246  5750  5750 D BluetoothMapService: stop()
11-24 11:24:24.247  5750  5750 D BluetoothMapAppObserver: deinitObservers()
11-24 11:24:24.247  5750  5750 D BluetoothMapAppObserver: removeReceiver()
11-24 11:24:24.248  3106  3106 D BluetoothMap: Proxy object disconnected
11-24 11:24:24.248  3106  3106 D MapProfile: Bluetooth service disconnected
,11-24 11:24:24.249  5750  5750 D SapService: Received stop request...Stopping profile...
11-24 11:24:24.249  5750  5750 V SapService: stop()
11-24 11:24:24.251  5750  5750 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:24.251  5750  5750 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:24.251  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:24.251  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:24.252  5624  5624 D BluetoothMap: Proxy object disconnected
11-24 11:24:24.252  5750  5773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:24.252  5624  5624 D MapProfile: Bluetooth service disconnected
11-24 11:24:24.253  5750  5773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:24.253  5750  5750 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:24.253  5750  5750 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:24.253  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:24.253  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 11:24:24.253  5750  5750 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 11:24:24.253  5750  5750 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 11:24:24.253  5750  5766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 11:24:24.253  5750  5773 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 11:24:24.253  5750  5766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 11:24:24.253  5750  5773 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 11:24:24.253  5750  5773 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 11:24:24.253  5750  5773 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 11:24:24.254  5750  5750 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:24.254  5750  5750 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:24.254  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 11:24:24.254  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:24.254  5750  5750 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 11:24:24.254  5750  5750 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 11:24:24.255  5750  5766 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 11:24:24.256  3106  3106 D BluetoothPbap: Proxy object disconnected
11-24 11:24:24.256  3106  3106 D PbapServerProfile: Bluetooth service disconnected
11-24 11:24:24.257  5750  5750 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:24.257  5750  5750 V BluetoothAdapterState: isTurningOn()=false
,11-24 11:24:24.257  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:24.257  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:24.257  5750  5750 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 11:24:24.257  5750  5750 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-24 11:24:24.258  5624  5624 D BluetoothPbap: Proxy object disconnected
11-24 11:24:24.258  5624  5624 D PbapServerProfile: Bluetooth service disconnected
11-24 11:24:24.259  5750  5750 D BluetoothMapService: MAP Service closeService in
11-24 11:24:24.259  5750  5750 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:24.259  5750  5750 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:24.259  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:24.259  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:24.259  5750  5750 D BluetoothMapService: cleanup()
,11-24 11:24:24.259  5750  5750 D BluetoothMapService: MAP Service closeService in
11-24 11:24:24.259  5750  5750 V BluetoothAdapterState: isTurningOff()=true
11-24 11:24:24.259  5750  5750 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:24.260  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:24.260  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:24.260  5750  5762 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 11:24:24.260  5750  5762 D BluetoothAdapterProperties: Setting state to 15
11-24 11:24:24.260  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-24 11:24:24.260  5750  5762 I BluetoothAdapterState: Entering BleOnState
11-24 11:24:24.261  5624  5636 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 11:24:24.262  5624  5634 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:24:24.263  3106  3124 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 11:24:24.263  3106  3957 D BluetoothPan: onBluetoothStateChange on: false
11-24 11:24:24.264   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:24:24.264  3106  3118 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:24:24.264  3106  3955 D BluetoothPbap: onBluetoothStateChange: up=false
,11-24 11:24:24.264  3732  3760 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:24:24.265   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 11:24:24.265  5624  5636 D BluetoothPan: onBluetoothStateChange on: false
,11-24 11:24:24.266  5624  5634 D BluetoothMap: onBluetoothStateChange: up=false
11-24 11:24:24.267   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:24:24.267  5624  5636 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 11:24:24.268  3106  3124 D BluetoothMap: onBluetoothStateChange: up=false
,11-24 11:24:24.269  3106  3957 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 11:24:24.270  5624  5634 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 11:24:24.270   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 11:24:24.271  5750  5762 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 11:24:24.271  5750  5762 D BluetoothAdapterProperties: Setting state to 16
11-24 11:24:24.271  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 11:24:24.271  5750  5762 D BluetoothAdapterProperties: onBleDisable
11-24 11:24:24.272  5750  5762 I BluetoothAdapterState: Entering PendingCommandState
11-24 11:24:24.272  5750  5763 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-24 11:24:24.274  5750  5773 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-24 11:24:24.274  5750  5773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:24:24.274  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:24:24.275  5750  5766 D BluetoothAdapterProperties: Scan Mode:20
11-24 11:24:24.276  5624  5624 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 11:24:24.276  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:24:24.282  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 11:24:24.284  5624  5624 D DockEventReceiver: finishStartingService: stopping service
,11-24 11:24:24.482  5750  5766 I bt_hci  : shut_down
,11-24 11:24:24.488  5750  5770 D bt_hwcfg: hw_epilog_process
11-24 11:24:24.488  5750  5770 I bt_vendor: low_power_mode_cb
,11-24 11:24:24.491  5750  5770 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 11:24:24.491  5750  5770 I bt_vendor: epilog_cb
11-24 11:24:24.491  5750  5770 I bt_hci  : epilog_finished_callback
,11-24 11:24:24.494  5750  5766 I bt_hci_h4: hal_close
,11-24 11:24:24.495  5750  5766 I bt_userial_vendor: device fd = 54 close
,11-24 11:24:24.606  5750  5763 D bt_stack_manager: event_shut_down_stack finished.
,11-24 11:24:24.606  5750  5762 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 11:24:24.609  5750  5762 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 11:24:24.609  5750  5750 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 11:24:24.610  5750  5750 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 11:24:24.610  5750  5750 D BtGatt.GattService: stop()
11-24 11:24:24.610  5750  5750 D BtGatt.AdvertiseManager: advertise clients cleared
,11-24 11:24:24.614  5750  5750 V BluetoothAdapterState: isTurningOff()=false
,11-24 11:24:24.614  5750  5750 V BluetoothAdapterState: isTurningOn()=false
11-24 11:24:24.614  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:24.614  5750  5750 V BluetoothAdapterState: isBleTurningOff()=true
11-24 11:24:24.614  5750  5762 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-24 11:24:24.614  5750  5762 D BluetoothAdapterProperties: Setting state to 10
11-24 11:24:24.614  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 11:24:24.615  5750  5762 I BluetoothAdapterState: Entering OffState
,11-24 11:24:24.615   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 11:24:24.621  5750  5750 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 11:24:24.622  5750  5750 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 11:24:24.623  5750  5750 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 11:24:24.623  5750  5763 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 11:24:24.627  5750  5750 I art     : System.exit called, status: 0
,11-24 11:24:24.627  5750  5750 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 11:24:24.649   926   936 I ActivityManager: Process com.android.bluetooth (pid 5750) has died
,11-24 11:24:26.565   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:27.566   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:27.649  3553  3553 I ConfigService: onDestroy
,11-24 11:24:28.567   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:29.191  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:24:29.191  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:24:29.196  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:29.197  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@97cdf04 removed from the list
,11-24 11:24:29.197  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:24:29.199  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:29.199  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@508c5b3 added. We now have 4 listener(s)
11-24 11:24:29.200  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:24:29.203  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:29.203  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@508c5b3 removed from the list
,11-24 11:24:29.203  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:24:29.205  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:29.206  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c6ae770 added. We now have 4 listener(s)
11-24 11:24:29.206  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:24:29.568   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:30.568   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:31.569   556   556 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 11:24:34.217  5556  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:24:34.253   926   943 I ActivityManager: Start proc 5806:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 11:24:34.339  5806  5806 D AdapterServiceConfig: Adding HeadsetService
,11-24 11:24:34.340  5806  5806 D AdapterServiceConfig: Adding A2dpService
11-24 11:24:34.340  5806  5806 D AdapterServiceConfig: Adding HidService
11-24 11:24:34.340  5806  5806 D AdapterServiceConfig: Adding HealthService
11-24 11:24:34.340  5806  5806 D AdapterServiceConfig: Adding PanService
11-24 11:24:34.341  5806  5806 D AdapterServiceConfig: Adding GattService
11-24 11:24:34.341  5806  5806 D AdapterServiceConfig: Adding BluetoothMapService
11-24 11:24:34.341  5806  5806 D AdapterServiceConfig: Adding SapService
,11-24 11:24:34.352   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@125be7c:true
,11-24 11:24:34.352  5806  5806 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 11:24:34.355  5806  5806 I bt_bluedroid: init
,11-24 11:24:34.358  5806  5818 I BluetoothAdapterState: Entering OffState
,11-24 11:24:34.360  5806  5819 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 11:24:34.360  5806  5819 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 11:24:34.360  5806  5819 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 11:24:34.360  5806  5819 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 11:24:34.361  5806  5806 I bt_bluedroid: get_profile_interface socket
,11-24 11:24:34.363  5806  5822 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 11:24:34.363  5806  5806 I bt_bluedroid: get_profile_interface sdp
11-24 11:24:34.365  5806  5822 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 11:24:34.368  5806  5817 I bt_bluedroid: config_hci_snoop_log
,11-24 11:24:34.370   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 11:24:34.374  5806  5818 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 11:24:34.374  5806  5818 D BluetoothAdapterProperties: Setting state to 14
11-24 11:24:34.375  5806  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 11:24:34.376  5806  5818 D BluetoothBondStateMachine: make
,11-24 11:24:34.378  5806  5823 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 11:24:34.381  5806  5818 I BluetoothAdapterState: Entering PendingCommandState
,11-24 11:24:34.382  5806  5806 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-24 11:24:34.385  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
11-24 11:24:34.386  5806  5806 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 11:24:34.387  5806  5806 D BtGatt.GattService: Received start request. Starting profile...
,11-24 11:24:34.387  5806  5806 D BtGatt.GattService: start()
11-24 11:24:34.387  5806  5806 I bt_bluedroid: get_profile_interface gatt
,11-24 11:24:34.388  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
11-24 11:24:34.389  5806  5806 D BtGatt.AdvertiseManager: advertise manager created
,11-24 11:24:34.395  5806  5806 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:34.395  5806  5806 V BluetoothAdapterState: isTurningOn()=false
,11-24 11:24:34.395  5806  5806 V BluetoothAdapterState: isBleTurningOn()=true
11-24 11:24:34.395  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:34.396  5806  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-24 11:24:34.398  5806  5818 I bt_bluedroid: bt_bluedroid
11-24 11:24:34.398  5806  5819 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-24 11:24:34.398  5806  5819 I bt_hci  : start_up
,11-24 11:24:34.404  5806  5819 I bt_vendor: alloc value 0xf42b7871
,11-24 11:24:34.404  5806  5819 I bt_vendor: init
11-24 11:24:34.404  5806  5819 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 11:24:34.404  5806  5819 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 11:24:34.513  5806  5819 D bt_hci  : start_up starting async portion
,11-24 11:24:34.513  5806  5826 I bt_hci  : event_finish_startup
,11-24 11:24:34.514  5806  5826 I bt_hci_h4: hal_open
11-24 11:24:34.514  5806  5826 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 11:24:34.513  5827  5827 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-24 11:24:34.517  5806  5826 I bt_userial_vendor: device fd = 54 open
,11-24 11:24:34.534  5806  5826 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 11:24:34.537  5806  5826 D bt_hwcfg: Chipset BCM4358A3
,11-24 11:24:34.538  5806  5826 D bt_hwcfg: Target name = [BCM4358A3]
,11-24 11:24:34.538  5806  5826 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 11:24:35.046  5806  5826 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 11:24:35.046  5806  5826 D bt_hwcfg: Settlement delay -- 100 ms
11-24 11:24:35.046  5806  5826 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 11:24:35.179  5806  5826 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 11:24:35.179  5806  5826 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-24 11:24:35.180  5806  5826 I bt_hwcfg: vendor lib fwcfg completed
,11-24 11:24:35.180  5806  5826 I bt_vendor: firmware callback
11-24 11:24:35.181  5806  5826 I bt_hci  : firmware_config_callback
,11-24 11:24:35.189  5806  5829 I bt_btu  : btu_task pending for preload complete event
11-24 11:24:35.189  5806  5829 I bt_btu_task: Bluetooth chip preload is complete
,11-24 11:24:35.190  5806  5829 I bt_btu  : btu_task received preload complete event
,11-24 11:24:35.197  5806  5829 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 11:24:35.197  5806  5829 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 11:24:35.197  5806  5829 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 11:24:35.197  5806  5829 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 11:24:35.197  5806  5829 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 11:24:35.197  5806  5829 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 11:24:35.197  5806  5829 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-24 11:24:35.198  5806  5829 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 11:24:35.198  5806  5829 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 11:24:35.198  5806  5829 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 11:24:35.198  5806  5829 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 11:24:35.198  5806  5829 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 11:24:35.198  5806  5829 I         : BTE_InitTraceLevels -- TRC_SMP
,11-24 11:24:35.199  5806  5829 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 11:24:35.199  5806  5829 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 11:24:35.283  5806  5829 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4235549
,11-24 11:24:35.283  5806  5829 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4235549 
,11-24 11:24:35.299  5806  5822 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 11:24:35.300  5806  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 11:24:35.301  5806  5822 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 11:24:35.304  5806  5822 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 11:24:35.309  5806  5822 D BluetoothAdapterProperties: Scan Mode:20
11-24 11:24:35.309  5806  5822 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 11:24:35.310  5806  5822 D bt_hci  : do_postload posting postload work item
11-24 11:24:35.310  5806  5826 I bt_hci  : event_postload
11-24 11:24:35.310  5806  5826 I bt_vendor: sco_config_cb
11-24 11:24:35.310  5806  5826 I bt_hci  : sco_config_callback postload finished.
,11-24 11:24:35.313  5806  5822 D bt_bte_conf: Device ID record 1 : primary
,11-24 11:24:35.313  5806  5822 D bt_bte_conf:   vendorId            = 000f
11-24 11:24:35.313  5806  5822 D bt_bte_conf:   vendorIdSource      = 0001
11-24 11:24:35.313  5806  5822 D bt_bte_conf:   product             = 1200
11-24 11:24:35.313  5806  5822 D bt_bte_conf:   version             = 1436
11-24 11:24:35.313  5806  5822 D bt_bte_conf:   clientExecutableURL = 
11-24 11:24:35.314  5806  5822 D bt_bte_conf:   serviceDescription  = 
11-24 11:24:35.314  5806  5822 D bt_bte_conf:   documentationURL    = 
,11-24 11:24:35.314  5806  5822 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 11:24:35.314  5806  5819 D bt_stack_manager: event_start_up_stack finished
11-24 11:24:35.315  5806  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 11:24:35.316  5806  5818 D BluetoothAdapterProperties: Setting state to 15
11-24 11:24:35.316  5806  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 11:24:35.317  5806  5826 I bt_vendor: low_power_mode_cb
11-24 11:24:35.317  5806  5818 I BluetoothAdapterState: Entering BleOnState
,11-24 11:24:35.324  5806  5818 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-24 11:24:35.324  5806  5818 D BluetoothAdapterProperties: Setting state to 11
11-24 11:24:35.325  5806  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 11:24:35.329  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
,11-24 11:24:35.330  5806  5806 D HeadsetService: Received start request. Starting profile...
11-24 11:24:35.334  5806  5806 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-24 11:24:35.335  5806  5806 D HeadsetStateMachine: make
,11-24 11:24:35.351  5806  5818 I BluetoothAdapterState: Entering PendingCommandState
,11-24 11:24:35.355  5806  5806 D HeadsetStateMachine: max_hf_connections = 1
,11-24 11:24:35.355  5806  5806 I bt_bluedroid: get_profile_interface handsfree
11-24 11:24:35.356  5806  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 11:24:35.356  5806  5822 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
11-24 11:24:35.359  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
11-24 11:24:35.360  5806  5806 D A2dpService: Received start request. Starting profile...
11-24 11:24:35.360  5806  5806 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 11:24:35.361  5806  5806 I bt_bluedroid: get_profile_interface avrcp
,11-24 11:24:35.367  5806  5806 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-24 11:24:35.367  5806  5806 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 11:24:35.367  5806  5806 D A2dpStateMachine: make
,11-24 11:24:35.369  5806  5806 I bt_bluedroid: get_profile_interface a2dp
,11-24 11:24:35.370  5806  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-24 11:24:35.371  5806  5836 D A2dpStateMachine: Enter Disconnected: -2
11-24 11:24:35.371  5806  5806 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 11:24:35.372  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
,11-24 11:24:35.373  5806  5806 D HidService: Received start request. Starting profile...
11-24 11:24:35.374  5806  5806 I bt_bluedroid: get_profile_interface hidhost
11-24 11:24:35.374  5806  5806 D HidService: setHidService(): set to: null
11-24 11:24:35.374  5806  5822 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf421656d
11-24 11:24:35.374  5806  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-24 11:24:35.375  5806  5806 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-24 11:24:35.376  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
11-24 11:24:35.377  5806  5806 D HealthService: Received start request. Starting profile...
11-24 11:24:35.377  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 11:24:35.379  5806  5806 I bt_bluedroid: get_profile_interface health
,11-24 11:24:35.380  5806  5806 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 11:24:35.381  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
11-24 11:24:35.382  5806  5806 D PanService: Received start request. Starting profile...
,11-24 11:24:35.382  5806  5806 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 11:24:35.382  5806  5806 I bt_bluedroid: get_profile_interface pan
11-24 11:24:35.383  5806  5822 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-24 11:24:35.385  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
,11-24 11:24:35.386  5806  5806 D BluetoothMapService: Received start request. Starting profile...
,11-24 11:24:35.386  5806  5806 D BluetoothMapService: start()
,11-24 11:24:35.390  5806  5806 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 11:24:35.391  5806  5806 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 11:24:35.391  5806  5806 D BluetoothMapAppObserver: createReceiver()
,11-24 11:24:35.393  5806  5806 D BluetoothMapAppObserver: initObservers()
,11-24 11:24:35.394  5806  5806 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 11:24:35.401  5806  5806 V SapService: SapBinder()
,11-24 11:24:35.401  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
,11-24 11:24:35.402  5806  5806 D SapService: Received start request. Starting profile...
11-24 11:24:35.402  5806  5806 V SapService: start()
,11-24 11:24:35.405  5806  5806 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:35.405  5806  5806 V BluetoothAdapterState: isTurningOn()=true
,11-24 11:24:35.405  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:35.405  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:35.406  5806  5806 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:35.406  5806  5834 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 11:24:35.406  5806  5806 V BluetoothAdapterState: isTurningOn()=true
11-24 11:24:35.406  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:35.406  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:35.406  5806  5806 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:35.407  5806  5806 V BluetoothAdapterState: isTurningOn()=true
,11-24 11:24:35.407  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 11:24:35.407  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:35.408  5806  5806 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:35.408  5806  5806 V BluetoothAdapterState: isTurningOn()=true
11-24 11:24:35.408  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:35.408  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:35.408  5806  5806 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:35.408  5806  5806 V BluetoothAdapterState: isTurningOn()=true
11-24 11:24:35.408  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:35.409  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:35.409  5806  5806 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:35.409  5806  5806 V BluetoothAdapterState: isTurningOn()=true
11-24 11:24:35.409  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:35.409  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 11:24:35.410  5806  5806 V BluetoothAdapterState: isTurningOff()=false
11-24 11:24:35.410  5806  5806 V BluetoothAdapterState: isTurningOn()=true
11-24 11:24:35.410  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:24:35.410  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:24:35.411  5806  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 11:24:35.411  5806  5818 D BluetoothAdapterProperties: ScanMode =  20
11-24 11:24:35.411  5806  5818 D BluetoothAdapterProperties: State =  11
11-24 11:24:35.413  5806  5822 D BluetoothAdapterProperties: Scan Mode:21
11-24 11:24:35.413  5806  5822 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 11:24:35.413  5806  5818 D BluetoothAdapterProperties: Setting state to 12
11-24 11:24:35.414  5806  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 11:24:35.414  5624  5634 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 11:24:35.414  5806  5818 I BluetoothAdapterState: Entering OnState
11-24 11:24:35.416  5624  5636 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 11:24:35.417  3106  3955 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 11:24:35.419  3106  3106 D BluetoothA2dp: Proxy object connected
11-24 11:24:35.419  3106  3118 D BluetoothPan: onBluetoothStateChange on: true
11-24 11:24:35.419  5624  5624 D BluetoothA2dp: Proxy object connected
11-24 11:24:35.420  5806  5806 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 11:24:35.421   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:24:35.421  3106  3957 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:24:35.421  5806  5806 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 11:24:35.421  3106  3955 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 11:24:35.423  5806  5806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:24:35.423  3732  3755 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:24:35.424   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 11:24:35.424  5806  5806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:24:35.425   926   926 D BluetoothA2dp: Proxy object connected
11-24 11:24:35.425  5624  5634 D BluetoothPan: onBluetoothStateChange on: true
,11-24 11:24:35.426  5806  5806 D ObexServerSockets: Succeed to create listening sockets 
11-24 11:24:35.426  5806  5806 D ObexServerSockets0: startAccept()
11-24 11:24:35.426  5806  5806 D ObexServerSockets0: prepareForNewConnect()
11-24 11:24:35.427  5624  5636 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 11:24:35.428   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 11:24:35.429  5624  5634 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 11:24:35.429  5806  5806 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 11:24:35.429  5806  5806 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 11:24:35.429  5806  5842 D ObexServerSockets0: Accepting socket connection...
11-24 11:24:35.429  5806  5843 D ObexServerSockets0: Accepting socket connection...
11-24 11:24:35.430  3106  3106 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 11:24:35.430  3106  3106 D PanProfile: Bluetooth service connected
,11-24 11:24:35.431  3106  3118 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 11:24:35.432  5624  5624 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 11:24:35.432  5624  5624 D PanProfile: Bluetooth service connected
11-24 11:24:35.432  5624  5624 D BluetoothMap: Proxy object connected
11-24 11:24:35.432  5624  5624 D MapProfile: Bluetooth service connected
11-24 11:24:35.432  5624  5624 D BluetoothMap: getConnectedDevices()
11-24 11:24:35.434  3106  3955 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 11:24:35.434  3106  3106 D BluetoothMap: Proxy object connected
11-24 11:24:35.434  3106  3106 D MapProfile: Bluetooth service connected
11-24 11:24:35.434  3106  3106 D BluetoothMap: getConnectedDevices()
11-24 11:24:35.435  5624  5634 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 11:24:35.436  3106  3106 D BluetoothInputDevice: Proxy object connected
11-24 11:24:35.436  3106  3106 D HidProfile: Bluetooth service connected
,11-24 11:24:35.437   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 11:24:35.439  5806  5806 D BluetoothMapService: onReceive
11-24 11:24:35.439  5806  5806 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 11:24:35.439  5806  5806 D BluetoothMapService: STATE_ON
11-24 11:24:35.439   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 11:24:35.440  5806  5845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:24:35.440  5624  5624 D BluetoothInputDevice: Proxy object connected
11-24 11:24:35.441  5624  5624 D HidProfile: Bluetooth service connected
11-24 11:24:35.441  5806  5845 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 11:24:35.441  5806  5845 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 11:24:35.446  5624  5624 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 11:24:35.451  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 11:24:35.451  5624  5624 D DockEventReceiver: finishStartingService: stopping service
,11-24 11:24:35.459  3106  3106 D BluetoothPbap: Proxy object connected
,11-24 11:24:35.459  5624  5624 D BluetoothPbap: Proxy object connected
11-24 11:24:35.459  3106  3106 D PbapServerProfile: Bluetooth service connected
11-24 11:24:35.459  5624  5624 D PbapServerProfile: Bluetooth service connected
,11-24 11:24:35.461  5806  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 11:24:35.465  5806  5806 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 11:24:35.465  5806  5806 D ObexServerSockets0: prepareForNewConnect()
,11-24 11:24:35.480  5806  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 11:24:35.481  5806  5855 I BtOppRfcommListener: Accept thread started.
,11-24 11:24:35.518  3732  3962 D BluetoothHeadset: Proxy object connected
,11-24 11:24:35.519  3106  3118 D BluetoothHeadset: Proxy object connected
,11-24 11:24:35.519  3106  3106 D HeadsetProfile: Bluetooth service connected
,11-24 11:24:35.519  5624  5844 D BluetoothHeadset: Proxy object connected
11-24 11:24:35.519   926   926 D BluetoothHeadset: Proxy object connected
11-24 11:24:35.520   926   926 D BluetoothHeadset: Proxy object connected
11-24 11:24:35.520   926   926 D BluetoothHeadset: Proxy object connected
11-24 11:24:35.520   926   943 D BluetoothHeadset: Proxy object connected
11-24 11:24:35.521  3106  3957 D BluetoothHeadset: Proxy object connected
11-24 11:24:35.521  3106  3106 D HeadsetProfile: Bluetooth service connected
,11-24 11:24:35.522  5624  5624 D HeadsetProfile: Bluetooth service connected
,11-24 11:24:35.524  3732  3760 D BluetoothHeadset: Proxy object connected
,11-24 11:24:35.529   926   943 D BluetoothHeadset: Proxy object connected
,11-24 11:24:35.538   926   943 D BluetoothHeadset: Proxy object connected
,11-24 11:24:36.570   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:37.570   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:38.572   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:39.235  5556  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:24:39.235  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:24:39.235  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:24:39.235  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 11:24:39.235  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:24:39.235  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:24:39.235  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:24:39.235  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:24:39.235  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 11:24:39.240  5556  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 11:24:39.241  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:39.241  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c6ae770 removed from the list
11-24 11:24:39.241  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:24:39.243  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:39.243  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca8dae9 added. We now have 4 listener(s)
11-24 11:24:39.243  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:24:39.247   926  3175 D WifiService: setWifiEnabled: false pid=5556, uid=10077
11-24 11:24:39.247   926  3175 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 11:24:39.573   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:40.574   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:41.574   556   556 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 11:24:44.256  5556  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:24:44.257   926   936 D WifiService: setWifiEnabled: true pid=5556, uid=10077
11-24 11:24:44.257   926   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 11:24:44.265   508   920 D SoftapController: Softap fwReload - Ok
,11-24 11:24:44.272   508   920 D CommandListener: Setting iface cfg
,11-24 11:24:44.273   508   920 D CommandListener: Trying to bring down wlan0
11-24 11:24:44.274   508   920 D CommandListener: Clearing all IP addresses on wlan0
,11-24 11:24:44.281   926  2923 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 11:24:44.890   926  2923 D wifi    : set interface wlan0 flags (UP)
,11-24 11:24:44.896   926  2923 I WifiHAL : Initializing wifi
11-24 11:24:44.896   926  2923 I WifiHAL : Creating socket
11-24 11:24:44.898   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 11:24:44.903   926  2923 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 11:24:44.904   926  2923 D wifi    : Did set static halHandle = 0x7f7b8e1dc0
11-24 11:24:44.904   926  2923 D wifi    : halHandle = 0x7f7b8e1dc0, mVM = 0x7f97ecd140, mCls = 0x1812
11-24 11:24:44.904   926  2923 D wifi    : array field set
11-24 11:24:44.904   926  2923 I WifiNative-HAL: interface[0] = wlan0
11-24 11:24:44.907   926  5860 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547533757888
11-24 11:24:44.907   926  5860 D wifi    : waitForHalEvents called, vm = 0x7f97ecd140, obj = 0x1812, env = 0x7f808be2c0
,11-24 11:24:44.964  5861  5861 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 11:24:45.008   926  2923 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 11:24:45.034  5861  5861 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 11:24:45.101  5861  5861 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 11:24:45.101  5861  5861 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 11:24:45.129   926  2923 D WifiConfigStore: Loading config and enabling all networks 
,11-24 11:24:45.153   926  2923 D WifiConfigStore: loaded 0 passpoint configs
,11-24 11:24:45.154   926  2923 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-24 11:24:45.154   926  2923 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 11:24:45.155   926  2923 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-24 11:24:45.155   926  2923 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-24 11:24:45.156   926  2923 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-24 11:24:45.157   926  2923 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 11:24:45.157   926  2923 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 11:24:45.158   926  2923 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 11:24:45.158   926  2923 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 11:24:45.158   926  2923 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 11:24:45.158   926  2923 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-24 11:24:45.158   926  2923 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 11:24:45.161   926  2923 D WifiNative-HAL: Setting external_sim to 1
,11-24 11:24:45.162  4969  4969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 11:24:45.162   926  2923 D wifi    : setting dfs flag to true, 0x7f7975e8e0
11-24 11:24:45.162   926  2923 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 11:24:45.162   926  2923 D wifi    : setting scan oui 0x7f7975e8e0
11-24 11:24:45.162   926  2923 D WifiHAL : Sending mac address OUI
,11-24 11:24:45.166   926  2923 E native  : do suspend false
,11-24 11:24:45.178   926  2923 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 11:24:45.178   926   926 D RttService: SCAN_AVAILABLE : 3
11-24 11:24:45.178   508   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 11:24:45.179   926  3038 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 11:24:45.180   508   920 D CommandListener: Setting iface cfg
,11-24 11:24:45.184   926  2922 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
,11-24 11:24:45.185   926  2922 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 11:24:45.197   926  2922 D WifiNative-HAL: p2pGetDeviceAddress
11-24 11:24:45.197   926  2922 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 11:24:45.204   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=247723 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=20 mControllerEnergyUsed=76 }
,11-24 11:24:48.271  5861  5861 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 11:24:48.277  5861  5861 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 11:24:48.282  5861  5861 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 11:24:48.356   926  2923 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-24 11:24:48.357   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 11:24:48.357   926  2923 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:24:48.372   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 11:24:48.410   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 11:24:48.417  5861  5861 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 11:24:49.275  5556  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:24:49.275  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:24:49.275  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:24:49.275  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:24:49.275  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:24:49.275  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:24:49.275  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:24:49.275  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:24:49.275  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 11:24:49.282  5556  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 11:24:49.283  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.283  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca8dae9 removed from the list
11-24 11:24:49.283  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:24:49.292  5556  5602 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-24 11:24:49.293  5556  5602 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-24 11:24:49.298  5556  5602 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@336e9ed Bundle[{}]
,11-24 11:24:49.299  5556  5602 I io.jxcore.node.LifeCycleMonitor: start: OK
11-24 11:24:49.299  5556  5602 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-24 11:24:49.300  5556  5602 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-24 11:24:49.301  5556  5602 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-24 11:24:49.303  5556  5602 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-24 11:24:49.305  5556  5602 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-24 11:24:49.315  5556  5602 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-24 11:24:49.316  5556  5602 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-24 11:24:49.316  5556  5602 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-24 11:24:49.319  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:24:49.319  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fce636e added. We now have 3 listener(s)
,11-24 11:24:49.321  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 11:24:49.321  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:24:49.321  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:24:49.322  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:49.322  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2400a0f added. We now have 4 listener(s)
11-24 11:24:49.322  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:24:49.323  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 11:24:49.325  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:24:49.325  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eef0a9c added. We now have 4 listener(s)
,11-24 11:24:49.327  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 11:24:49.327  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:24:49.327  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:24:49.328  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:49.328  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ab3ca5 added. We now have 5 listener(s)
11-24 11:24:49.328  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:24:49.328  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:24:49.328  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:24:49.328  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:24:49.328  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:24:49.329  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:24:49.329  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:24:49.329  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fce636e removed from the list
11-24 11:24:49.329  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.329  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2400a0f removed from the list
,11-24 11:24:49.329  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:24:49.329  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.329  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.331  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.331  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.332  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.332  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:24:49.332  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:24:49.332  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.332  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2400a0f not in the list
11-24 11:24:49.332  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.332  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.334  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.334  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.334  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.334  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:24:49.335  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:24:49.335  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.335  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ab3ca5 removed from the list
11-24 11:24:49.335  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:24:49.335  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:24:49.335  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:24:49.335  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eef0a9c removed from the list
11-24 11:24:49.336  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:24:49.336  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f01487a added. We now have 3 listener(s)
11-24 11:24:49.338  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:24:49.338  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:24:49.338  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:24:49.338  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 11:24:49.338  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffd382b added. We now have 4 listener(s)
11-24 11:24:49.338  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:24:49.340  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 11:24:49.342  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:24:49.342  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2303488 added. We now have 4 listener(s)
,11-24 11:24:49.344  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:24:49.344  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:24:49.344  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:24:49.344  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:49.344  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b7fe21 added. We now have 5 listener(s)
,11-24 11:24:49.344  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:24:49.344  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:24:49.344  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-24 11:24:49.345  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 11:24:49.345  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:24:49.345  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 11:24:49.346  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 11:24:49.350  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 11:24:49.350  5556  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 11:24:49.350  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 11:24:49.353  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.353  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 11:24:49.354  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 11:24:49.354  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-24 11:24:49.354  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 11:24:49.370  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.371  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 11:24:49.371  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 11:24:49.371  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:24:49.371  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:24:49.371  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.372  5556  5602 D BluetoothAdapter: STATE_ON
,11-24 11:24:49.375  5806  5847 D BtGatt.GattService: registerClient() - UUID=27004f3c-612e-4bfe-a3b0-122fcc9f4bd6
11-24 11:24:49.376  5806  5822 D BtGatt.GattService: onClientRegistered() - UUID=27004f3c-612e-4bfe-a3b0-122fcc9f4bd6, clientIf=5
,11-24 11:24:49.378  5556  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 11:24:49.379  5806  5817 D BtGatt.GattService: start scan with filters
,11-24 11:24:49.382  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 11:24:49.382  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.382  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 11:24:49.382  5806  5825 D BtGatt.ScanManager: handling starting scan
11-24 11:24:49.382  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.382  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 11:24:49.383  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 11:24:49.383  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.383  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:24:49.383  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 11:24:49.383  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.383  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.383  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.383  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.384  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 11:24:49.384  5806  5825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17b7096
11-24 11:24:49.384  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.386  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.386  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:24:49.386  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.386  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.386  5556  5602 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 11:24:49.386  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 11:24:49.386  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 11:24:49.386  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:24:49.386  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) lef,t
11-24 11:24:49.387  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:24:49.387  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 11:24:49.386  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.390  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.390  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.390  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.390  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:24:49.390  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:24:49.390  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.390  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 11:24:49.390  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:24:49.390  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.390  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.390  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.390  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 11:24:49.390  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.391  5806  5822 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-24 11:24:49.391  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.392  5806  5825 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 11:24:49.392  5556  5602 D BluetoothAdapter: STATE_ON
11-24 11:24:49.392  5806  5847 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 11:24:49.392  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 11:24:49.393  5556  5602 D BluetoothAdapter: STATE_ON
11-24 11:24:49.393  5806  5816 D BtGatt.GattService: stopScan() - queue size =1
11-24 11:24:49.394  5806  5841 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 11:24:49.394  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 11:24:49.394  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.394  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:24:49.395  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.395  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.395  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.395  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.395  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 11:24:49.395  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.395  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.395  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.395  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:24:49.395  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 11:24:49.396  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 11:24:49.396  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.397  5806  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-24 11:24:49.397  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.397  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.397  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:24:49.398  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.398  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.398  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:24:49.398  5806  5825 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:24:49.398  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:24:49.398  5806  5825 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 11:24:49.398  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:24:49.398  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.398  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 11:24:49.398  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:24:49.398  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.398  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.398  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 11:24:49.398  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:24:49.399  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.399  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.400  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.400  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:24:49.400  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.400  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:24:49.400  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:24:49.400  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.400  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:24:49.400  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:24:49.400  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:24:49.400  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f01487a removed from the list
11-24 11:24:49.400  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.401  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffd382b removed from the list
11-24 11:24:49.401  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:24:49.401  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.401  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.402  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.402  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.402  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.402  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:24:49.402  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:24:49.402  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.402  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffd382b not in the list
11-24 11:24:49.402  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.403  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.404  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.404  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.405  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.405  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 11:24:49.405  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:24:49.405  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.405  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b7fe21 removed from the list
11-24 11:24:49.405  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:24:49.405  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:24:49.405  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:24:49.405  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2303488 removed from the list
11-24 11:24:49.406  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:24:49.406  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc6cd2 added. We now have 3 listener(s)
11-24 11:24:49.407  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:24:49.407  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:24:49.407  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:24:49.407  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:49.407  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ce81a3 added. We now have 4 listener(s)
11-24 11:24:49.407  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:24:49.408  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 11:24:49.409  5806  5822 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 11:24:49.409  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.409  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:24:49.409  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47f0ca0 added. We now have 4 listener(s)
11-24 11:24:49.410  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:24:49.410  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:24:49.411  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:24:49.411  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:49.411  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b15059 added. We now have 5 listener(s)
11-24 11:24:49.411  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:24:49.411  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 11:24:49.412  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:24:49.412  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 11:24:49.412  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 11:24:49.412  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:24:49.413  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 11:24:49.415  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 11:24:49.417  5806  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 11:24:49.417  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:24:49.418  5806  5825 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 11:24:49.419  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 11:24:49.419  5556  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 11:24:49.419  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 11:24:49.421  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.421  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 11:24:49.422  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 11:24:49.422  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 11:24:49.422  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 11:24:49.423  5806  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:24:49.424  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.424  5806  5822 E BtGatt.ContextMap: Context not found for ID 5
,11-24 11:24:49.425  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.425  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 11:24:49.425  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 11:24:49.425  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:24:49.425  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:24:49.425  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.426  5556  5602 D BluetoothAdapter: STATE_ON
11-24 11:24:49.428  5806  5847 D BtGatt.GattService: registerClient() - UUID=bf9859bb-f23d-4834-8413-ef3d61a348ff
,11-24 11:24:49.429  5806  5822 D BtGatt.GattService: onClientRegistered() - UUID=bf9859bb-f23d-4834-8413-ef3d61a348ff, clientIf=5
11-24 11:24:49.429  5556  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 11:24:49.429  5806  5841 D BtGatt.GattService: start scan with filters
11-24 11:24:49.430  5806  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 11:24:49.430  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.430  5806  5825 D BtGatt.ScanManager: stopping BLe Batch
11-24 11:24:49.431  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 11:24:49.431  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.431  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 11:24:49.431  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.431  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 11:24:49.431  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-24 11:24:49.431  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.431  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:24:49.431  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 11:24:49.431  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.432  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.432  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.432  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.433  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 11:24:49.433  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.435  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.435  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:24:49.435  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.435  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.436  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:24:49.436  5806  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 11:24:49.436  5556  5602 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-24 11:24:49.436  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.436  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.436  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:24:49.436  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:24:49.436  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:24:49.436  5806  5825 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 11:24:49.436  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:24:49.436  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:24:49.436  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 11:24:49.436  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:24:49.436  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:24:49.436  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc6cd2 removed from the list
11-24 11:24:49.436  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.436  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ce81a3 removed from the list
11-24 11:24:49.436  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:24:49.436  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:24:49.436  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:24:49.437  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.437  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 11:24:49.437  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 11:24:49.437  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:24:49.437  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:24:49.437  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.438  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.438  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.438  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.438  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:24:49.438  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.438  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:24:49.438  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-24 11:24:49.438  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.438  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.438  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ce81a3 not in the list
11-24 11:24:49.438  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:24:49.438  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:24:49.438  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.438  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 11:24:49.438  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:24:49.438  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.438  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.438  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.438  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 11:24:49.439  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.440  5556  5602 D BluetoothAdapter: STATE_ON
11-24 11:24:49.440  5806  5841 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 11:24:49.440  5806  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:24:49.440  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.440  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 11:24:49.441  5556  5602 D BluetoothAdapter: STATE_ON
,11-24 11:24:49.442  5806  5816 D BtGatt.GattService: stopScan() - queue size =0
11-24 11:24:49.442  5806  5825 D BtGatt.ScanManager: handling starting scan
,11-24 11:24:49.443  5806  5817 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 11:24:49.443  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 11:24:49.443  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.443  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:24:49.443  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.444  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.444  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.444  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.444  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 11:24:49.444  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.444  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.444  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.444  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:24:49.444  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 11:24:49.444  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:24:49.445  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.446  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.446  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:24:49.446  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.446  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.446  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:24:49.446  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:24:49.446  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.446  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:24:49.446  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b15059 removed from the list
11-24 11:24:49.446  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:24:49.446  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:24:49.446  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:24:49.446  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:24:49.446  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:24:49.446  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47f0ca0 removed from the list
11-24 11:24:49.446  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.446  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 11:24:49.446  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:24:49.446  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.447  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.447  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.447  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:24:49.447  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.447  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 11:24:49.447  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.447  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87cc42a added. We now have 3 listener(s)
11-24 11:24:49.447  5806  5822 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 11:24:49.447  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.447  5806  5825 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 11:24:49.448  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.448  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.448  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.448  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:24:49.448  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:24:49.448  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:24:49.448  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:49.448  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360821b added. We now have 4 listener(s)
11-24 11:24:49.448  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:24:49.449  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 11:24:49.449  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:24:49.450  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39dcfb8 added. We now have 4 listener(s)
11-24 11:24:49.451  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:24:49.451  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:24:49.451  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:24:49.452  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:49.452  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcbb191 added. We now have 5 listener(s)
11-24 11:24:49.452  5806  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 11:24:49.452  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:24:49.452  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.452  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:24:49.452  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 11:24:49.452  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-24 11:24:49.452  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:24:49.452  5806  5825 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:24:49.452  5806  5825 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 11:24:49.452  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 11:24:49.454  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 11:24:49.459  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 11:24:49.459  5556  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 11:24:49.459  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 11:24:49.463  5806  5822 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 11:24:49.463  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:24:49.463  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.463  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 11:24:49.464  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 11:24:49.464  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 11:24:49.464  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 11:24:49.467  5806  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 11:24:49.468  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:24:49.469  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.469  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 11:24:49.469  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 11:24:49.469  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:24:49.469  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:24:49.469  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.469  5806  5825 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 11:24:49.470  5556  5602 D BluetoothAdapter: STATE_ON
,11-24 11:24:49.471  5806  5847 D BtGatt.GattService: registerClient() - UUID=dba53866-130b-49d2-8b0e-d15e008d52f6
11-24 11:24:49.472  5806  5822 D BtGatt.GattService: onClientRegistered() - UUID=dba53866-130b-49d2-8b0e-d15e008d52f6, clientIf=5
,11-24 11:24:49.472  5556  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 11:24:49.472  5806  5846 D BtGatt.GattService: start scan with filters
11-24 11:24:49.474  5806  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:24:49.474  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:24:49.475  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 11:24:49.475  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.475  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 11:24:49.475  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.475  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 11:24:49.476  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.476  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 11:24:49.476  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.476  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:24:49.476  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 11:24:49.476  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 11:24:49.476  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.477  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.477  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.477  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.477  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 11:24:49.478  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.478  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.478  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.478  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.480  5806  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 11:24:49.480  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.480  5806  5825 D BtGatt.ScanManager: stopping BLe Batch
11-24 11:24:49.481  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.481  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:24:49.481  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:24:49.481  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.481  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:24:49.481  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:24:49.481  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.481  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:24:49.481  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:24:49.481  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:24:49.482  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:24:49.482  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:24:49.482  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:24:49.482  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87cc42a removed from the list
11-24 11:24:49.482  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.482  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360821b removed from the list
,11-24 11:24:49.482  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:24:49.482  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:24:49.482  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:24:49.482  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.482  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 11:24:49.482  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 11:24:49.482  5556  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:24:49.482  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:24:49.482  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.484  5806  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 11:24:49.484  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.484  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.484  5806  5825 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:24:49.484  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.484  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.484  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:24:49.484  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:24:49.484  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.484  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360821b not in the list
11-24 11:24:49.485  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:24:49.485  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.485  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 11:24:49.485  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:24:49.485  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.485  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.485  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.485  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 11:24:49.485  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.486  5556  5602 D BluetoothAdapter: STATE_ON
11-24 11:24:49.486  5806  5846 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 11:24:49.486  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 11:24:49.486  5556  5602 D BluetoothAdapter: STATE_ON
11-24 11:24:49.487  5806  5847 D BtGatt.GattService: stopScan() - queue size =0
11-24 11:24:49.487  5806  5841 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.488  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:24:49.488  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 11:24:49.489  5806  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:24:49.489  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.489  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:24:49.489  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.490  5806  5825 D BtGatt.ScanManager: handling starting scan
11-24 11:24:49.490  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.490  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:24:49.490  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.490  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.490  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 11:24:49.490  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:24:49.490  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:24:49.491  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcbb191 removed from the list
11-24 11:24:49.491  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:24:49.491  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:24:49.491  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:24:49.491  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39dcfb8 removed from the list
11-24 11:24:49.491  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:24:49.491  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:24:49.491  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:24:49.491  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.491  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 11:24:49.491  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:24:49.491  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 11:24:49.491  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.491  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.491  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:24:49.492  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.492  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.492  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:24:49.492  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@255ae82 added. We now have 3 listener(s)
11-24 11:24:49.493  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.493  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.493  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:24:49.493  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:24:49.494  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:24:49.494  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:24:49.494  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:49.494  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4331993 added. We now have 4 listener(s)
11-24 11:24:49.494  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:24:49.494  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 11:24:49.495  5806  5822 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 11:24:49.495  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:24:49.495  5806  5825 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 11:24:49.495  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:24:49.495  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63eddd0 added. We now have 4 listener(s)
11-24 11:24:49.496  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:24:49.497  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:24:49.497  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:24:49.497  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:24:49.497  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3a01c9 added. We now have 5 listener(s)
11-24 11:24:49.497  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:24:49.497  5556  5602 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:24:49.497  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:24:49.497  5556  5602 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:24:49.497  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:24:49.497  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:24:49.497  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:24:49.498  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@255ae82 removed from the list
11-24 11:24:49.498  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.498  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4331993 removed from the list
,11-24 11:24:49.498  5556  5602 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:24:49.498  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.498  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.500  5806  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 11:24:49.500  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.500  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.500  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.500  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.500  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:24:49.500  5806  5825 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:24:49.500  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:24:49.500  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.500  5806  5825 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 11:24:49.500  5556  5602 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4331993 not in the list
,11-24 11:24:49.500  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.500  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.502  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.502  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 11:24:49.502  5556  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 11:24:49.502  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:24:49.502  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:24:49.502  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:24:49.502  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3a01c9 removed from the list
11-24 11:24:49.502  5556  5602 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:24:49.502  5556  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:24:49.502  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:24:49.502  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63eddd0 removed from the list
11-24 11:24:49.503  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 11:24:49.503  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-24 11:24:49.503  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 11:24:49.503  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:24:49.503  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 11:24:49.503  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:24:49.509  5806  5822 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 11:24:49.509  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:24:49.514  5806  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 11:24:49.514  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:24:49.515  5806  5825 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:24:49.520  5806  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:24:49.520  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.521  5806  5822 E BtGatt.ContextMap: Context not found for ID 5
,11-24 11:24:49.526  5806  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 11:24:49.526  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.527  5806  5825 D BtGatt.ScanManager: stopping BLe Batch
,11-24 11:24:49.532  5806  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 11:24:49.532  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:24:49.532  5806  5825 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:24:49.537  5806  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:24:49.537  5806  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:24:49.768  5861  5861 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
,11-24 11:24:49.899  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 11:24:49.947  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 11:24:49.993  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 11:24:51.575   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:51.637  5556  5863 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 11:24:51.637  5556  5863 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:24:52.455  5556  5863 W !!      : call onHalfStreamCopied
,11-24 11:24:52.455  5556  5863 I testCopyDataAndClose: closing input stream
,11-24 11:24:52.575   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:52.781  5861  5861 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 11:24:52.848   926  2923 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 11:24:52.851   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 11:24:52.851   926  2923 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:24:52.865   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 11:24:52.892   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 11:24:53.235  5556  5863 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 11:24:53.235  5556  5863 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:24:53.236  5556  5863 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 11:24:53.236  5556  5863 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 11:24:53.236  5556  5863 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 11:24:53.236  5556  5863 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 11:24:53.236  5556  5863 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 11:24:53.236  5556  5863 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 11:24:53.236  5556  5863 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 11:24:53.236  5556  5863 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 11:24:53.236  5556  5863 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 11:24:53.576   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:54.129  5861  5861 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
,11-24 11:24:54.577   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:55.578   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:24:56.579   556   556 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 11:24:57.522  5556  5864 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:24:57.522  5556  5864 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:24:57.538  5861  5861 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 11:24:57.593   926  2923 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 11:24:57.595   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 11:24:57.595   926  2923 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:24:57.612   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 11:24:57.649   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 11:24:58.903  5861  5861 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
,11-24 11:24:59.522  5556  5602 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-24 11:24:59.522  5556  5602 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 11:24:59.522  5556  5602 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-24 11:24:59.576  5556  5864 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 11:24:59.576  5556  5864 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:24:59.576  5556  5864 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-24 11:24:59.662  5556  5865 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 11:24:59.662  5556  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:25:01.267  5556  5865 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 11:25:01.267  5556  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:25:01.268  5556  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].,
11-24 11:25:01.268  5556  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 11:25:01.268  5556  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 11:25:01.268  5556  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 11:25:01.268  5556  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 11:25:01.268  5556  5865 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 11:25:01.268  5556  5865 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 11:25:01.268  5556  5865 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 11:25:01.268  5556  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 11:25:02.810  5861  5861 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 11:25:02.864   926  2923 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-24 11:25:02.866   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 11:25:02.867   926  2923 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:25:02.877   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 11:25:02.905   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 11:25:04.145  5861  5861 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
,11-24 11:25:04.148  5861  5861 I wpa_supplicant: wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=0 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED
11-24 11:25:04.149   926  2923 D WifiStateMachine: ConnectModeState SSID state=temp-disabled nid=0 [id=0 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED]
,11-24 11:25:04.150   926  2923 E WifiConfigStore: SSID temp disabled for  "NG700"WPA_PSK had autoJoinStatus=0 self added false ephemeral false
11-24 11:25:04.150   926  2923 E WifiConfigStore:  message=id=0 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED
,11-24 11:25:05.397  5556  5866 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:25:05.397  5556  5866 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:25:05.397  5556  5866 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:25:05.397  5556  5866 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 11:25:05.397  5556  5866 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 11:25:05.397  5556  5866 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:25:05.397  5556  5866 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 11:25:05.398  5556  5866 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 11:25:05.398  5556  5866 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 11:25:05.398  5556  5866 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-24 11:25:05.398  5556  5866 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 11:25:05.398  5556  5866 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:25:05.398  5556  5866 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-24 11:25:05.400  5556  5602 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-24 11:25:05.403  5556  5867 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:25:05.403  5556  5867 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:25:05.404  5556  5867 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-24 11:25:05.404  5556  5867 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:25:05.404  5556  5867 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 11:25:05.404  5556  5867 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-24 11:25:05.405  5556  5867 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:25:05.405  5556  5867 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 11:25:05.410  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 11:25:05.410  5556  5602 I jxcore-log: 
,11-24 11:25:05.411  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG UnitTest_app: 'Number of passed tests:  81'
11-24 11:25:05.411  5556  5602 I jxcore-log: 
11-24 11:25:05.411  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG UnitTest_app: 'Number of failed tests:  1'
11-24 11:25:05.411  5556  5602 I jxcore-log: 
11-24 11:25:05.411  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 11:25:05.411  5556  5602 I jxcore-log: 
11-24 11:25:05.412  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG UnitTest_app: 'Total duration:  91650'
11-24 11:25:05.412  5556  5602 I jxcore-log: 
11-24 11:25:05.412  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG UnitTest_app: 'Failures: 
11-24 11:25:05.412  5556  5602 I jxcore-log:  mDiscoveryManager1 state should not be NOT_STARTED
11-24 11:25:05.412  5556  5602 I jxcore-log: Expected: is not <NOT_STARTED>
11-24 11:25:05.412  5556  5602 I jxcore-log:      but: was <NOT_STARTED>
11-24 11:25:05.412  5556  5602 I jxcore-log: '
11-24 11:25:05.412  5556  5602 I jxcore-log: 
,11-24 11:25:05.413  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-24 11:25:05.413  5556  5602 I jxcore-log: 
11-24 11:25:05.414  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 11:25:05.414  5556  5602 I jxcore-log: 
,11-24 11:25:05.417  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 11:25:05.417  5556  5602 I jxcore-log: 
11-24 11:25:05.418  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 11:25:05.418  5556  5602 I jxcore-log: 
11-24 11:25:05.418  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 11:25:05.418  5556  5602 I jxcore-log: 
11-24 11:25:05.419  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 11:25:05.419  5556  5602 I jxcore-log: 
11-24 11:25:05.419  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:25:05.419  5556  5602 I jxcore-log: 
11-24 11:25:05.419  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:25:05.419  5556  5602 I jxcore-log: 
11-24 11:25:05.419  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:25:05.419  5556  5602 I jxcore-log: 
11-24 11:25:05.420  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 11:25:05.420  5556  5602 I jxcore-log: 
11-24 11:25:05.420  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 11:25:05.420  5556  5602 I jxcore-log: 
11-24 11:25:05.421  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 11:25:05.421  5556  5602 I jxcore-log: 
11-24 11:25:05.421  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 11:25:05.421  5556  5602 I jxcore-log: 
11-24 11:25:05.421  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:25:05.421  5556  5602 I jxcore-log: 
11-24 11:25:05.421  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:25:05.421  5556  5602 I jxcore-log: 
11-24 11:25:05.421  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:25:05.421  5556  5602 I jxcore-log: 
11-24 11:25:05.422  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:25:05.422  5556  5602 I jxcore-log: 
,11-24 11:25:05.422  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:25:05.422  5556  5602 I jxcore-log: 
11-24 11:25:05.422  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 11:25:05.422  5556  5602 I jxcore-log: 
11-24 11:25:05.422  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 11:25:05.422  5556  5602 I jxcore-log: 
11-24 11:25:05.423  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 11:25:05.423  5556  5602 I jxcore-log: 
11-24 11:25:05.423  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 11:25:05.423  5556  5602 I jxcore-log: 
11-24 11:25:05.423  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 11:25:05.423  5556  5602 I jxcore-log: 
11-24 11:25:05.423  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 11:25:05.423  5556  5602 I jxcore-log: 
11-24 11:25:05.425  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 11:25:05.425  5556  5602 I jxcore-log: 
11-24 11:25:05.425  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 11:25:05.425  5556  5602 I jxcore-log: 
,11-24 11:25:05.426  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 11:25:05.426  5556  5602 I jxcore-log: 
11-24 11:25:05.426  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 11:25:05.426  5556  5602 I jxcore-log: 
11-24 11:25:05.426  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-24 11:25:05.426  5556  5602 I jxcore-log: 
11-24 11:25:05.426  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:25:05.427  5556  5602 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-24 11:25:05.427  5556  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:25:05.427  5556  5602 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,11-24 11:25:05.427  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:25:05.427  5556  5602 I jxcore-log: 
11-24 11:25:05.427  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:25:05.427  5556  5602 I jxcore-log: 
11-24 11:25:05.427  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:25:05.427  5556  5602 I jxcore-log: 
11-24 11:25:05.428  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:25:05.428  5556  5602 I jxcore-log: 
,11-24 11:25:05.428  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:25:05.428  5556  5602 I jxcore-log: 
11-24 11:25:05.428  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:25:05.428  5556  5602 I jxcore-log: 
11-24 11:25:05.431  5556  5556 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-24 11:25:05.431  5556  5556 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-24 11:25:05.433  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 11:25:05.433  5556  5602 I jxcore-log: 
11-24 11:25:05.434  5556  5602 I jxcore-log: 2016-11-24 10:25:05 - WARN testUtils: 'myNameCallback not set!'
11-24 11:25:05.434  5556  5602 I jxcore-log: 
,11-24 11:25:07.525  5556  5602 I jxcore-log: 2016-11-24 10:25:07 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 11:25:07.525  5556  5602 I jxcore-log: 
,11-24 11:25:07.527  5556  5602 I jxcore-log: 2016-11-24 10:25:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 11:25:07.527  5556  5602 I jxcore-log: 
,11-24 11:25:07.880  5556  5602 I jxcore-log: 2016-11-24 10:25:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 11:25:07.880  5556  5602 I jxcore-log: 
,11-24 11:25:07.890  5556  5602 I jxcore-log: 2016-11-24 10:25:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 11:25:07.890  5556  5602 I jxcore-log: 
,11-24 11:25:09.007  5556  5602 I jxcore-log: 2016-11-24 10:25:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 11:25:09.007  5556  5602 I jxcore-log: 
,11-24 11:25:09.201  5556  5602 I jxcore-log: 2016-11-24 10:25:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 11:25:09.201  5556  5602 I jxcore-log: 
,11-24 11:25:09.206  5556  5602 I jxcore-log: 2016-11-24 10:25:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 11:25:09.206  5556  5602 I jxcore-log: 
,11-24 11:25:09.210  5556  5602 I jxcore-log: 2016-11-24 10:25:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 11:25:09.210  5556  5602 I jxcore-log: 
,11-24 11:25:09.696  5556  5602 I jxcore-log: 2016-11-24 10:25:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 11:25:09.696  5556  5602 I jxcore-log: 
,11-24 11:25:09.741  5556  5602 I jxcore-log: 2016-11-24 10:25:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 11:25:09.741  5556  5602 I jxcore-log: 
,11-24 11:25:09.754  5556  5602 I jxcore-log: 2016-11-24 10:25:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 11:25:09.754  5556  5602 I jxcore-log: 
,11-24 11:25:09.759  5556  5602 I jxcore-log: 2016-11-24 10:25:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 11:25:09.759  5556  5602 I jxcore-log: 
,11-24 11:25:10.032  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 11:25:10.032  5556  5602 I jxcore-log: 
,11-24 11:25:10.163  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 11:25:10.163  5556  5602 I jxcore-log: 
,11-24 11:25:10.536  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 11:25:10.536  5556  5602 I jxcore-log: 
,11-24 11:25:10.544  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 11:25:10.544  5556  5602 I jxcore-log: 
,11-24 11:25:10.548  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 11:25:10.548  5556  5602 I jxcore-log: 
,11-24 11:25:10.554  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 11:25:10.554  5556  5602 I jxcore-log: 
,11-24 11:25:10.559  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 11:25:10.559  5556  5602 I jxcore-log: 
,11-24 11:25:10.587  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 11:25:10.587  5556  5602 I jxcore-log: 
,11-24 11:25:10.623  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 11:25:10.623  5556  5602 I jxcore-log: 
,11-24 11:25:10.630  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 11:25:10.630  5556  5602 I jxcore-log: 
,11-24 11:25:10.637  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 11:25:10.637  5556  5602 I jxcore-log: 
,11-24 11:25:10.652  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 11:25:10.652  5556  5602 I jxcore-log: 
,11-24 11:25:10.668  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 11:25:10.668  5556  5602 I jxcore-log: 
,11-24 11:25:10.674  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 11:25:10.674  5556  5602 I jxcore-log: 
,11-24 11:25:10.680  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 11:25:10.680  5556  5602 I jxcore-log: 
,11-24 11:25:10.693  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 11:25:10.693  5556  5602 I jxcore-log: 
,11-24 11:25:10.710  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 11:25:10.710  5556  5602 I jxcore-log: 
,11-24 11:25:10.725  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 11:25:10.725  5556  5602 I jxcore-log: 
,11-24 11:25:10.736  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 11:25:10.736  5556  5602 I jxcore-log: 
,11-24 11:25:10.748  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 11:25:10.748  5556  5602 I jxcore-log: 
,11-24 11:25:10.759  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 11:25:10.759  5556  5602 I jxcore-log: 
,11-24 11:25:10.772  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 11:25:10.772  5556  5602 I jxcore-log: 
,11-24 11:25:10.782  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 11:25:10.782  5556  5602 I jxcore-log: 
,11-24 11:25:10.789  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 11:25:10.789  5556  5602 I jxcore-log: 
,11-24 11:25:10.811  5556  5602 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 11:25:10.812  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 11:25:10.812  5556  5602 I jxcore-log: 
,11-24 11:25:10.846  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 11:25:10.846  5556  5602 I jxcore-log: 
,11-24 11:25:10.877  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 11:25:10.877  5556  5602 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 11:25:10.877  5556  5602 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 11:25:10.877  5556  5602 I jxcore-log: emit@events.js:82:1
11-24 11:25:10.877  5556  5602 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 11:25:10.877  5556  5602 I jxcore-log: emit@events.js:82:1''
11-24 11:25:10.877  5556  5602 I jxcore-log: 
,11-24 11:25:10.877  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - DEBUG CoordinatedClient: 'test client failed'
11-24 11:25:10.877  5556  5602 I jxcore-log: 
11-24 11:25:10.882  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 11:25:10.882  5556  5602 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 11:25:10.882  5556  5602 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 11:25:10.882  5556  5602 I jxcore-log: emit@events.js:82:1
11-24 11:25:10.882  5556  5602 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 11:25:10.882  5556  5602 I jxcore-log: emit@events.js:82:1''
11-24 11:25:10.882  5556  5602 I jxcore-log: 
11-24 11:25:10.882  5556  5602 I jxcore-log: 2016-11-24 10:25:10 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 11:25:10.882  5556  5602 I jxcore-log: 
,11-24 11:25:11.452  5868  5868 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 11:25:11.468  5868  5868 D AndroidRuntime: CheckJNI is OFF
,11-24 11:25:11.497  5868  5868 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 11:25:11.531  5868  5868 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 11:25:11.549  5868  5868 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 11:25:11.556   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-24 11:25:11.557   926   939 I ActivityManager: Killing 5556:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 11:25:11.581   556   556 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:25:11.670   926   936 D GraphicsStats: Buffer count: 2
11-24 11:25:11.670   926  3567 I WindowState: WIN DEATH: Window{aadbad6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-24 11:25:11.670   926  2924 D WifiService: Client connection lost with reason: 4
,11-24 11:25:11.682   926   939 W ActivityManager: Force removing ActivityRecord{a0b8b7f u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-24 11:25:11.697   926   950 I art     : Starting a blocking GC Explicit
,11-24 11:25:11.703   926  3818 W ActivityManager: Spurious death for ProcessRecord{373c17 0:com.test.thalitest/u0a77}, curProc for 5556: null
,11-24 11:25:11.723   936   936 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[16486]" dev="sockfs" ino=16486 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 11:25:11.723   936   936 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[16486]" dev="sockfs" ino=16486 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 11:25:11.726   926   936 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5556 uid 10077
,11-24 11:25:11.735  3639  3639 I Keyboard.Facilitator: onFinishInput()
,11-24 11:25:11.790  3942  5881 I MicroRecognitionRnrImpl: Starting detection.
,11-24 11:25:11.792   926   950 I art     : Explicit concurrent mark sweep GC freed 60321(4MB) AllocSpace objects, 26(932KB) LOS objects, 33% free, 29MB/43MB, paused 1.768ms total 94.430ms
,11-24 11:25:11.794  3942  5882 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@d8af85e
,11-24 11:25:11.802   513  2971 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-24 11:25:11.802   513  5884 I AudioFlinger: AudioFlinger's thread 0xf1f40000 ready to run
,11-24 11:25:11.804  3942  5882 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@d8af85e
,11-24 11:25:11.810   926   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-24 11:25:11.812  5868  5868 I art     : System.exit called, status: 0
,11-24 11:25:11.812  5868  5868 I AndroidRuntime: VM exiting with result code 0.
,11-24 11:25:11.815   513  5884 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-24 11:25:11.815   513  5884 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-24 11:25:11.815   513  5884 I ACDB-LOADER: ACDB AFE returned = -19
11-24 11:25:11.815   513  5884 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
,11-24 11:25:11.815   513  5884 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
,11-24 11:25:11.815   513  5884 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-24 11:25:11.821   513  5884 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-24 11:25:11.824   926   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 11:25:11.831  5806  5806 D BluetoothMapAppObserver: onReceive
11-24 11:25:11.831  5806  5806 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-24 11:25:11.834   926  2883 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-24 11:25:11.835  3639  3639 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-24 11:25:11.835  4061  4144 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-24 11:25:11.859  3378  5888 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 11:25:11.860  3639  5887 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 11:25:11.872  3639  5887 I Decoder : createOrResetDecoder
,11-24 11:25:11.901   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 11:25:11.903  3732  3732 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 11:25:11.909  3942  3942 I HotwordWorkerImpl: onReady
,11-24 11:25:11.935  3553  3553 I ConfigService: onCreate
,11-24 11:25:11.943  3553  3553 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-24 11:25:11.944  3553  3553 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-24 11:25:11.940    27    27 W kworker/1:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 11:25:11.947    27    27 W kworker/1:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 11:25:11.958  3927  5895 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-24 11:25:11.959  3927  5895 D AccountUtils: Clearing selected account for com.test.thalitest
,11-24 11:25:11.970  3639  5887 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-24 11:25:11.970  3927  5895 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-24 11:25:11.973  3378  5888 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-24 11:25:11.973    27    27 W kworker/1:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 11:25:11.984  3927  5895 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:25:11.984  3927  5895 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:25:11.985  3927  5895 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 11:25:11.988  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-24 11:25:11.988  3927  3927 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-24 11:25:11.991  3927  5895 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
--------- beginning of crash
11-24 11:25:11.992  3378  5888 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-24 11:25:11.992  3378  5888 E AndroidRuntime: Process: android.process.acore, PID: 3378
11-24 11:25:11.992  3378  5888 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLi,teDatabase.java:1499)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:25:11.992  3378  5888 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 11:25:11.993  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-24 11:25:11.993  3927  3927 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-24 11:25:11.999  3927  5901 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:25:11.999  3927  5901 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:25:11.999  3927  5901 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 11:25:12.001  3927  5901 W SQLiteOpenHelper: Opened metrics.db in read-only mode
11-24 11:25:12.001  3927  5901 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
11-24 11:25:12.001  3927  5901 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-24 11:25:12.002  3927  5901 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,11-24 11:25:12.003  3927  5901 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-24 11:25:12.003  3927  5901 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-24 11:25:12.003  3927  5901 E AndroidRuntime: Process: com.google.android.gms, PID: 3927
11-24 11:25:12.003  3927  5901 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-24 11:25:12.003  3927  5901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 11:25:12.003  3927  5901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 11:25:12.003  3927  5901 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 11:25:12.003  3927  5901 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 11:25:12.003  3927  5901 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 11:25:12.003  3927  5901 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-24 11:25:12.003  3927  5901 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-24 11:25:12.003  3927  5901 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 11:25:12.003  3927  5901 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 11:25:12.003  3927  5901 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:25:12.003  3927  5901 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: Can't write: system_app_crash
11-24 11:25:12.004   926  5904 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 11:25:12.004   926  5904 E DropBoxManagerService: 	... 5 more
,11-24 11:25:12.010   406   406 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[35082]" dev="sockfs" ino=35082 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:25:12.010   406   406 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[35082]" dev="sockfs" ino=35082 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:25:12.013   406   406 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34129]" dev="sockfs" ino=34129 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:25:12.016   926  5906 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-24 11:25:12.013   406   406 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[34129]" dev="sockfs" ino=34129 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:25:12.020  3942  5905 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-24 11:25:12.023   926  5907 E DropBoxManagerService: Can't write: system_app_crash
11-24 11:25:12.023   926  5907 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
11-24 11:25:12.023   926  5907 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 11:25:12.023   926  5907 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 11:25:12.023   926  5907 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 11:25:12.023   926  5907 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 11:25:12.023   926  5907 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 11:25:12.023   926  5907 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 11:25:12.023   926  5907 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 11:25:12.023   926  5907 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 11:25:12.023   926  5907 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 11:25:12.023   926  5907 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 11:25:12.023   926  5907 E DropBoxManagerService: 	... 5 more
,11-24 11:25:12.040  3639  5887 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-24 11:25:12.044  3756  3978 E ReflectionEngine: Failed to save models
11-24 11:25:12.044  3756  3978 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 11:25:12.044  3756  3978 E ReflectionEngine: 	... 16 more
,11-24 11:25:12.046  3639  5887 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,11-24 11:25:12.046  3639  5887 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-24 11:25:12.049  3639  5887 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-24 11:25:12.050  3639  5887 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-24 11:25:12.050  3639  5887 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-24 11:25:12.050  3639  5887 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-24 11:25:12.055  3639  5887 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,11-24 11:25:12.055  3639  5887 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-24 11:25:12.056  3639  5887 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-24 11:25:12.056  3639  5887 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-24 11:25:12.056  3639  5887 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-24 11:25:12.056  3639  5887 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-24 11:25:12.057   926  3817 I ActivityManager: Start proc 5910:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-24 11:25:12.073  3927  5902 W BaseAppContext: Using Auth Proxy for data requests.
,11-24 11:25:12.078  3927  5902 W BaseAppContext: Using Auth Proxy for data requests.
,11-24 11:25:12.080  3927  5895 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
,11-24 11:25:12.086  3927  5916 I GMPM-SVC: App measurement is starting up
,11-24 11:25:12.095  3927  3927 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-24 11:25:12.095  3927  5916 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-24 11:25:12.096  3927  5916 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-24 11:25:12.099  3927  5916 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
11-24 11:25:12.099  3927  5916 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
,11-24 11:25:12.100  3927  5916 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 11:25:12.100  3927  5916 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
,11-24 11:25:12.100  3927  5916 E GMPM-SVC: Opening the database failed, dropping and recreating it
11-24 11:25:12.101  3927  5916 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
11-24 11:25:12.101  3927  5916 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 11:25:12.102  3927  5916 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-24 11:25:12.103  3927  5916 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-24 11:25:12.103  3927  5916 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,11-24 11:25:12.104  3927  5916 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,11-24 11:25:12.122   926  2923 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 11:25:12.122   926   939 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{44f3397 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{40f3731 3927 com.google.android.gms/10012/u0 remote:e8b67d8}: process crashing
11-24 11:25:12.122   926  2923 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 11:25:12.122   926  2923 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:25:12.128   926  3771 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3927 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-24 11:25:12.172  3927  5899 W DriveInitializer: Awaiting to be initialized
,11-24 11:25:12.173  3927  5921 W DriveInitializer: Background init thread started
,11-24 11:25:12.245  3756  3984 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-24 11:25:12.349   382   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
