#### Test 89624796d0595a7_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-09 11:52:43.236  3922  4152 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-09 11:52:43.308  3922  4152 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-09 11:52:43.522   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
11-09 11:52:43.683  5590  5590 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-09 11:52:43.688  5590  5590 D AndroidRuntime: CheckJNI is OFF
11-09 11:52:43.716  5590  5590 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-09 11:52:43.760  5590  5590 I Radio-JNI: register_android_hardware_Radio DONE
11-09 11:52:43.775  5590  5590 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-09 11:52:43.789   926  5098 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-09 11:52:43.808  5590  5590 D AndroidRuntime: Shutting down VM
11-09 11:52:43.821  3908  5588 W SearchService: Abort, client detached.
11-09 11:52:43.834  3908  3908 I HotwordDetector: Closing mic
11-09 11:52:43.835  3908  4134 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@9aa5b78
11-09 11:52:43.835  3908  4138 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-09 11:52:43.843   926  3368 I ActivityManager: Start proc 5602:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-09 11:52:43.904   512  4141 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-09 11:52:43.905   512  4141 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-09 11:52:43.910   512  4141 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-09 11:52:43.910   512  4141 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-09 11:52:43.911   512  2973 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-09 11:52:43.919  3908  4137 I MicroRecognitionRnrImpl: Detection finished
11-09 11:52:43.919  3908  4135 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-09 11:52:43.946  5602  5602 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-09 11:52:43.974  5602  5602 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-09 11:52:44.029  5602  5602 I LibraryLoader: Time to load native libraries: 52 ms (timestamps 4683-4735)
11-09 11:52:44.029  5602  5602 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-09 11:52:44.053  5602  5602 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ef71a65}
,11-09 11:52:44.053  5602  5602 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-09 11:52:44.053  5602  5602 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-09 11:52:44.056  5602  5602 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-09 11:52:44.057  5602  5602 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-09 11:52:44.113  5602  5602 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-09 11:52:44.122  5602  5602 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-09 11:52:44.122  5602  5602 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-09 11:52:44.122  5602  5602 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-09 11:52:44.122  5602  5602 I Adreno  : Build Date                       : 12/06/15
11-09 11:52:44.122  5602  5602 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-09 11:52:44.122  5602  5602 I Adreno  : Local Branch                     : mybranch17112971
11-09 11:52:44.122  5602  5602 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-09 11:52:44.122  5602  5602 I Adreno  : Remote Branch                    : NONE
11-09 11:52:44.122  5602  5602 I Adreno  : Reconstruct Branch               : NOTHING
,11-09 11:52:44.157   926   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a20f5b:true
,11-09 11:52:44.184   406   406 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[28225]" dev="sockfs" ino=28225 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 11:52:44.184   406   406 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[28225]" dev="sockfs" ino=28225 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 11:52:44.198  5602  5602 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-09 11:52:44.206  5602  5602 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-09 11:52:44.227  2942  2942 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34105]" dev="sockfs" ino=34105 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 11:52:44.227  2942  2942 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34105]" dev="sockfs" ino=34105 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-09 11:52:44.231  5602  5639 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-09 11:52:44.227  3784  3784 W Binder_7: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[21244]" dev="sockfs" ino=21244 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:52:44.234  5602  5626 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-09 11:52:44.227  3784  3784 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[21244]" dev="sockfs" ino=21244 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:52:44.253  5602  5639 I OpenGLRenderer: Initialized EGL, version 1.4
,11-09 11:52:44.314  3914  3914 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33135]" dev="sockfs" ino=33135 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:52:44.322   926   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +499ms
11-09 11:52:44.323  3635  3635 I Keyboard.Facilitator: onFinishInput()
11-09 11:52:44.314  3914  3914 W Binder_8: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33135]" dev="sockfs" ino=33135 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-09 11:52:44.317  3090  3090 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33134]" dev="sockfs" ino=33134 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:52:44.317  3090  3090 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33134]" dev="sockfs" ino=33134 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:52:44.362  5602  5602 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5602
,11-09 11:52:44.427  5602  5602 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-09 11:52:44.559  5602  5641 D jxcore_app_log: JniHelper::setJavaVM(0xf50fc000), pthread_self() = -599000784
,11-09 11:52:44.563  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-09 11:52:44.563  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-09 11:52:44.563  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-09 11:52:44.563  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-09 11:52:44.563  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-09 11:52:44.563  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@327f523 added. We now have 1 listener(s)
,11-09 11:52:44.565  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-09 11:52:44.566  5602  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:52:44.566  5602  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-09 11:52:44.567  5602  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-09 11:52:44.569  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c612d9e added. We now have 1 listener(s)
11-09 11:52:44.569  5602  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-09 11:52:44.572   926  2952 D WifiService: New client listening to asynchronous messages
11-09 11:52:44.573  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-09 11:52:44.573  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-09 11:52:44.573  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-09 11:52:44.573  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-09 11:52:44.573  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-09 11:52:44.575  5602  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 11:52:44.575  5602  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-09 11:52:44.579  5602  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-09 11:52:44.579  5602  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 11:52:44.579  5602  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:52:44.579  5602  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:52:44.579  5602  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:52:44.579  5602  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:52:44.579  5602  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:52:44.579  5602  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:52:44.579  5602  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 11:52:44.579  5602  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-09 11:52:44.579  5602  5641 D io.jxcore.node.ConnectivityMonitor: start: OK
11-09 11:52:44.579  5602  5641 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-09 11:52:44.581  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:52:44.584  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:52:44.596  5602  5602 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-09 11:52:45.060  5602  5648 W jxcore-log: Initializing JXcore engine
,11-09 11:52:45.060  5602  5648 W jxcore-log: JXcore engine is ready
,11-09 11:52:45.084  5648  5648 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11388 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-09 11:52:45.084  5648  5648 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14462]" dev="sockfs" ino=14462 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-09 11:52:45.084  5648  5648 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2901 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-09 11:52:45.084  5648  5648 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33111]" dev="sockfs" ino=33111 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-09 11:52:45.096  5602  5648 W jxcore-log: Starting JXcore engine
,11-09 11:52:45.151  5602  5648 W jxcore-log: Platform android
11-09 11:52:45.151  5602  5648 W jxcore-log: 
,11-09 11:52:45.151  5602  5648 W jxcore-log: Process ARCH arm
11-09 11:52:45.151  5602  5648 W jxcore-log: 
,11-09 11:52:45.292  5602  5648 I jxcore-log: JXcore Cordova bridge is ready!
11-09 11:52:45.292  5602  5648 I jxcore-log: 
,11-09 11:52:45.293  5602  5648 W jxcore-log: JXcore engine is started
,11-09 11:52:45.308  5602  5641 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-09 11:52:45.316  5602  5602 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-09 11:52:47.378  3529  3529 I ConfigService: onDestroy
,11-09 11:52:48.835   926  3784 I ActivityManager: Killing 5103:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-09 11:52:54.919  5602  5648 I jxcore-log: 2016-11-09 10:52:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-09 11:52:54.919  5602  5648 I jxcore-log: 
,11-09 11:52:54.921  5602  5648 I jxcore-log: 2016-11-09 10:52:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-09 11:52:54.921  5602  5648 I jxcore-log: 
,11-09 11:52:54.926  5602  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 11:52:54.926  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:52:54.926  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:52:54.926  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:52:54.926  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:52:54.926  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:52:54.926  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:52:54.926  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 11:52:54.927  5602  5648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 11:52:54.929  5602  5648 I jxcore-log: 2016-11-09 10:52:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-09 11:52:54.929  5602  5648 I jxcore-log: 
,11-09 11:52:54.930  5602  5648 I jxcore-log: 2016-11-09 10:52:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-09 11:52:54.930  5602  5648 I jxcore-log: 
,11-09 11:52:55.179  5602  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-09 11:52:55.179  5602  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc0c0c added. We now have 2 listener(s)
11-09 11:52:55.179  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:52:55.180  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-09 11:52:55.180  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-09 11:52:55.180  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-09 11:52:55.180  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad4f955 added. We now have 2 listener(s)
,11-09 11:52:55.180  5602  5648 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-09 11:52:55.181  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-09 11:52:55.182  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 11:52:55.185  5602  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 11:52:55.185  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:52:55.185  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:52:55.185  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:52:55.185  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:52:55.185  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:52:55.185  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:52:55.185  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 11:52:55.186  5602  5648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 11:52:55.187  5602  5648 D io.jxcore.node.ConnectivityMonitor: start: OK
11-09 11:52:55.187  5602  5648 D ExecuteNativeTests: Running unit tests
11-09 11:52:55.188  5602  5648 D BluetoothAdapter: enable(): BT is already enabled..!
11-09 11:52:55.188   926  3090 D WifiService: setWifiEnabled: true pid=5602, uid=10077
11-09 11:52:55.188   926  3090 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 11:52:55.194  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:52:55.199  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:52:56.981  3908  5654 W CronetSyncConnectionRcs: Upload content type not set.
,11-09 11:52:57.053  4784  4832 D Finsky  : [188] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-09 11:52:57.053  4784  4784 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-09 11:52:59.365   926  2950 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-09 11:53:03.524   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:04.525   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:04.693   926   926 I ActivityManager: Killing 5285:com.android.settings/1000 (adj 15): empty #17
,11-09 11:53:04.715   926   926 I ActivityManager: Killing 5218:org.codeaurora.ims/1001 (adj 15): empty #18
,11-09 11:53:05.194  5602  5648 I com.test.thalitest.ThaliTestRunner: Running UT
,11-09 11:53:05.254  5602  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-09 11:53:05.255  5602  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@847751f added. We now have 3 listener(s)
11-09 11:53:05.255  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:05.255  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-09 11:53:05.256  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-09 11:53:05.256  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-09 11:53:05.256  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@116806c added. We now have 3 listener(s)
11-09 11:53:05.256  5602  5648 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-09 11:53:05.257  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-09 11:53:05.259  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 11:53:05.262  5602  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 11:53:05.262  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:05.262  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:05.262  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:05.262  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:05.262  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:05.262  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:53:05.262  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 11:53:05.263  5602  5648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:05.263  5602  5648 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-09 11:53:05.267  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-09 11:53:05.267  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-09 11:53:05.267  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 11:53:05.267  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 11:53:05.267  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 11:53:05.268  5602  5648 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-09 11:53:05.269  5602  5648 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-09 11:53:05.269  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-09 11:53:05.269  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 11:53:05.269  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 11:53:05.269  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-09 11:53:05.270  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,11-09 11:53:05.270  5602  5648 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-09 11:53:05.272  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-09 11:53:05.273  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,11-09 11:53:05.273  5602  5648 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-09 11:53:05.274  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:05.279  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:05.279  5602  5648 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-09 11:53:05.280  5602  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-09 11:53:05.280  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-09 11:53:05.280  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 11:53:05.280  5602  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-09 11:53:05.280  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-09 11:53:05.280  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 11:53:05.280  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-09 11:53:05.281  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-09 11:53:05.281  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-09 11:53:05.281  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-09 11:53:05.281  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-09 11:53:05.282  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-09 11:53:05.282  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 11:53:05.282  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-09 11:53:05.282  5602  5602 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-09 11:53:05.282  5602  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-09 11:53:05.284  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 11:53:05.284  5602  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-09 11:53:05.284  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-09 11:53:05.287  5602  5658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 11:53:05.284  4613  4613 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32129]" dev="sockfs" ino=32129 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 11:53:05.288  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-09 11:53:05.288  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-09 11:53:05.289  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 11:53:05.290  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.290  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 11:53:05.290  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:05.290  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-09 11:53:05.290  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-09 11:53:05.290  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.290  5602  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-09 11:53:05.290  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.290  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.291  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.291  5602  5648 D BluetoothAdapter: STATE_ON
,11-09 11:53:05.294  4602  4798 D BtGatt.GattService: registerClient() - UUID=9647955c-f1e0-44f6-a6e6-645a33e841cf
11-09 11:53:05.284  4613  4613 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32129]" dev="sockfs" ino=32129 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 11:53:05.295  4602  4662 D BtGatt.GattService: onClientRegistered() - UUID=9647955c-f1e0-44f6-a6e6-645a33e841cf, clientIf=5
11-09 11:53:05.296  5602  5612 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-09 11:53:05.298  4602  4664 D BtGatt.AdvertiseManager: message : 0
,11-09 11:53:05.302  4602  4664 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 11:53:05.318  4602  4662 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 11:53:05.326  4602  4662 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-09 11:53:05.327  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.327  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.327  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:05.327  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.327  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.328  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.328  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.328  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.328  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 11:53:05.328  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 11:53:05.328  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.329  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.329  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.329  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.329  5602  5648 I io.jxcore.node.ConnectionHelper: start: OK
11-09 11:53:05.329  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 11:53:05.330  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-09 11:53:05.330  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.330  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 11:53:05.330  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
,11-09 11:53:05.330  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.331  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.331  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 11:53:05.331  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-09 11:53:05.331  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.331  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.331  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-09 11:53:05.331  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:05.335  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.335  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-09 11:53:05.335  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.335  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.335  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-09 11:53:05.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.336  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-09 11:53:05.526   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:05.832  5602  5648 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-09 11:53:05.833  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-09 11:53:05.833  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-09 11:53:05.833  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-09 11:53:05.833  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-09 11:53:05.833  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-09 11:53:05.833  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-09 11:53:05.833  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-09 11:53:05.833  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-09 11:53:05.833  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-09 11:53:05.833  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-09 11:53:05.834  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-09 11:53:05.834  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-09 11:53:05.834  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-09 11:53:05.834  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-09 11:53:05.834  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-09 11:53:05.834  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-09 11:53:05.834  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-09 11:53:05.835  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-09 11:53:05.836  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-09 11:53:05.836  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-09 11:53:05.836  5602  5648 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-09 11:53:05.836  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-09 11:53:05.836  5602  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-09 11:53:05.836  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-09 11:53:05.836  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-09 11:53:05.836  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-09 11:53:05.837  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-09 11:53:05.837  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-09 11:53:05.837  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-09 11:53:05.837  5602  5658 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-09 11:53:05.837  5602  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-09 11:53:05.837  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-09 11:53:05.838  5602  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-09 11:53:05.838  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-09 11:53:05.838  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-09 11:53:05.838  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-09 11:53:05.838  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-09 11:53:05.839  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.839  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.840  5602  5648 D BluetoothAdapter: STATE_ON
11-09 11:53:05.841  5602  5648 D BluetoothLeScanner: could not find callback wrapper
11-09 11:53:05.841  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-09 11:53:05.841  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.841  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.841  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-09 11:53:05.841  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.842  4602  4664 D BtGatt.AdvertiseManager: message : 1
11-09 11:53:05.844  4602  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
11-09 11:53:05.857  4602  4662 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 11:53:05.857  4602  4662 D BtGatt.GattService: Client app is not null!
,11-09 11:53:05.859  4602  4613 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-09 11:53:05.860  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 11:53:05.860  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.860  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-09 11:53:05.860  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.861  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.861  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.861  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-09 11:53:05.861  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-09 11:53:05.861  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.862  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.862  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-09 11:53:05.862  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.864  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.864  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 11:53:05.864  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.865  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.865  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.865  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.865  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.865  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-09 11:53:05.866  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-09 11:53:05.868  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-09 11:53:05.868  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.869  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.870  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.870  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.871  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-09 11:53:05.871  5602  5602 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-09 11:53:05.872  5602  5648 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-09 11:53:05.872  5602  5648 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-09 11:53:05.872  5602  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,11-09 11:53:05.872  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-09 11:53:05.873  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-09 11:53:05.873  5602  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-09 11:53:05.873  5602  5602 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-09 11:53:05.873  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-09 11:53:05.873  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 11:53:05.874  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-09 11:53:05.875  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-09 11:53:05.875  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-09 11:53:05.875  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-09 11:53:05.875  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-09 11:53:05.875  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-09 11:53:05.875  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 11:53:05.875  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-09 11:53:05.878  5602  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-09 11:53:05.878  5602  5661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 11:53:05.877  4613  4613 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32137]" dev="sockfs" ino=32137 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 11:53:05.879  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 11:53:05.879  5602  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-09 11:53:05.879  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-09 11:53:05.881  5602  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-09 11:53:05.877  4613  4613 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32137]" dev="sockfs" ino=32137 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-09 11:53:05.884  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-09 11:53:05.885  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-09 11:53:05.885  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 11:53:05.888  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.888  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 11:53:05.888  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:05.888  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
,11-09 11:53:05.889  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 11:53:05.889  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.889  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.890  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.890  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.891  5602  5648 D BluetoothAdapter: STATE_ON
,11-09 11:53:05.894  4602  4807 D BtGatt.GattService: registerClient() - UUID=2e757008-b3f2-48eb-a57f-280730c912ac
,11-09 11:53:05.895  4602  4662 D BtGatt.GattService: onClientRegistered() - UUID=2e757008-b3f2-48eb-a57f-280730c912ac, clientIf=5
11-09 11:53:05.895  5602  5613 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-09 11:53:05.896  4602  4664 D BtGatt.AdvertiseManager: message : 0
,11-09 11:53:05.898  4602  4664 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 11:53:05.910  4602  4662 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 11:53:05.917  4602  4662 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-09 11:53:05.918  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.918  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.918  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:05.918  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.918  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.918  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.918  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.918  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.918  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 11:53:05.920  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 11:53:05.920  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:05.921  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.921  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.921  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:05.922  5602  5648 I io.jxcore.node.ConnectionHelper: start: OK
11-09 11:53:05.922  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 11:53:05.922  5602  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-09 11:53:05.922  5602  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  false
,11-09 11:53:05.923  5602  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-09 11:53:05.924  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.924  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.924  5602  5602 D BluetoothAdapter: STATE_ON
11-09 11:53:05.924  5602  5602 D BluetoothLeScanner: could not find callback wrapper
11-09 11:53:05.924  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-09 11:53:05.925  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:05.925  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.925  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-09 11:53:05.925  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.925  4602  4664 D BtGatt.AdvertiseManager: message : 1
11-09 11:53:05.926  4602  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-09 11:53:05.931  4602  4662 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 11:53:05.931  4602  4662 D BtGatt.GattService: Client app is not null!
,11-09 11:53:05.932  4602  4615 D BtGatt.GattService: unregisterClient() - clientIf=5
11-09 11:53:05.932  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-09 11:53:05.933  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.933  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
11-09 11:53:05.933  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.933  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.933  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.933  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-09 11:53:05.933  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-09 11:53:05.933  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.933  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.933  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.933  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.933  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-09 11:53:05.933  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-09 11:53:05.934  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 11:53:05.934  5602  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-09 11:53:05.934  5602  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-09 11:53:05.939  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-09 11:53:05.940  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-09 11:53:05.940  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 11:53:05.944  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.944  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 11:53:05.944  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:05.944  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-09 11:53:05.944  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 11:53:05.944  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.944  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.944  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.944  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
,11-09 11:53:05.945  5602  5602 D BluetoothAdapter: STATE_ON
11-09 11:53:05.948  4602  4798 D BtGatt.GattService: registerClient() - UUID=b35b580e-6ef4-4203-b654-56fc9dae84fa
11-09 11:53:05.948  4602  4662 D BtGatt.GattService: onClientRegistered() - UUID=b35b580e-6ef4-4203-b654-56fc9dae84fa, clientIf=5
11-09 11:53:05.948  5602  5613 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-09 11:53:05.949  4602  4664 D BtGatt.AdvertiseManager: message : 0
11-09 11:53:05.951  4602  4664 D BtGatt.AdvertiseManager: starting multi advertising
11-09 11:53:05.961  4602  4662 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-09 11:53:05.967  4602  4662 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-09 11:53:05.968  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.968  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.968  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:05.968  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.968  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.968  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.968  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.968  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.968  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 11:53:05.970  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 11:53:05.970  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.971  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.971  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.972  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.972  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-09 11:53:05.973  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 11:53:05.973  5602  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-09 11:53:05.975  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.975  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:05.976  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-09 11:53:05.976  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 11:53:05.976  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.976  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.976  4602  4664 D BtGatt.AdvertiseManager: message : 1
11-09 11:53:05.977  4602  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
11-09 11:53:05.982  4602  4662 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 11:53:05.982  4602  4662 D BtGatt.GattService: Client app is not null!
,11-09 11:53:05.982  4602  4615 D BtGatt.GattService: unregisterClient() - clientIf=5
11-09 11:53:05.983  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 11:53:05.983  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.983  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
11-09 11:53:05.983  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.983  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.983  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:05.983  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-09 11:53:05.984  5602  5602 D BluetoothAdapter: STATE_ON
11-09 11:53:05.987  4602  4806 D BtGatt.GattService: registerClient() - UUID=ec3e1a65-225f-47f9-a024-f5f10c871437
11-09 11:53:05.988  4602  4662 D BtGatt.GattService: onClientRegistered() - UUID=ec3e1a65-225f-47f9-a024-f5f10c871437, clientIf=5
11-09 11:53:05.988  5602  5613 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-09 11:53:05.989  4602  4664 D BtGatt.AdvertiseManager: message : 0
11-09 11:53:05.991  4602  4664 D BtGatt.AdvertiseManager: starting multi advertising
11-09 11:53:06.001  4602  4662 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-09 11:53:06.006  4602  4662 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-09 11:53:06.006  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.006  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.006  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:06.006  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.006  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.006  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.006  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.007  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.007  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.007  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Already running
11-09 11:53:06.007  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.007  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.007  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.007  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 11:53:06.008  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 11:53:06.008  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.009  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.009  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.009  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.009  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 11:53:06.009  5602  5602 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-09 11:53:06.009  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 11:53:06.010  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.010  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.010  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to RUNNING
11-09 11:53:06.010  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.010  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.010  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.010  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 11:53:06.010  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-09 11:53:06.010  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.010  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.010  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-09 11:53:06.010  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.011  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.011  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.011  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.011  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.011  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.011  5602  5602 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-09 11:53:06.012  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.012  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:06.012  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-09 11:53:06.510  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-09 11:53:06.511  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-09 11:53:06.527   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:07.528   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:08.529   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-09 11:53:10.926  5602  5662 E io.jxcore.node.ConnectionHelperTest: Discovery manager didn't start after 5s!
,11-09 11:53:10.934  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-09 11:53:10.935  5602  5648 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-09 11:53:10.935  5602  5648 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-09 11:53:10.935  5602  5648 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-09 11:53:10.935  5602  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-09 11:53:10.935  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-09 11:53:10.936  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-09 11:53:10.936  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-09 11:53:10.936  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-09 11:53:10.936  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-09 11:53:10.936  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-09 11:53:10.936  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-09 11:53:10.936  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-09 11:53:10.936  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-09 11:53:10.936  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-09 11:53:10.936  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.938  4602  4664 D BtGatt.AdvertiseManager: message : 1
11-09 11:53:10.941  4602  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-09 11:53:10.954  4602  4662 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 11:53:10.955  4602  4662 D BtGatt.GattService: Client app is not null!
,11-09 11:53:10.956  4602  4798 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-09 11:53:10.956  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-09 11:53:10.956  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.957  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-09 11:53:10.957  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.957  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.957  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-09 11:53:10.957  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:10.957  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 11:53:10.957  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:10.957  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-09 11:53:10.958  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-09 11:53:10.958  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.958  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.958  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.958  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.960  5602  5648 D BluetoothAdapter: STATE_ON
,11-09 11:53:10.965  4602  4615 D BtGatt.GattService: registerClient() - UUID=3c3f1490-243a-49ab-8dd9-c08b59a2fe1f
,11-09 11:53:10.965  4602  4662 D BtGatt.GattService: onClientRegistered() - UUID=3c3f1490-243a-49ab-8dd9-c08b59a2fe1f, clientIf=5
11-09 11:53:10.966  5602  5649 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-09 11:53:10.967  4602  4664 D BtGatt.AdvertiseManager: message : 0
11-09 11:53:10.969  4602  4664 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 11:53:10.979  4602  4662 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 11:53:10.985  4602  4662 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-09 11:53:10.986  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 11:53:10.986  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.986  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.986  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:10.986  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.986  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.986  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.986  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.986  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:10.986  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:10.986  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-09 11:53:10.986  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-09 11:53:10.986  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 11:53:10.987  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 11:53:10.987  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:10.987  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-09 11:53:10.987  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:10.987  5602  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-09 11:53:10.987  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 11:53:10.987  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-09 11:53:10.987  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-09 11:53:10.987  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:10.987  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:10.987  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:10.988  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Already started
,11-09 11:53:10.988  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-09 11:53:10.988  5602  5648 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
11-09 11:53:10.988  5602  5648 I io.jxcore.node.ConnectionHelper: start: OK
,11-09 11:53:15.992  5602  5663 E io.jxcore.node.ConnectionHelperTest: Discovery manager didn't start after 5s!
,11-09 11:53:15.997  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-09 11:53:15.998  5602  5648 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-09 11:53:16.002  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,11-09 11:53:16.003  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-09 11:53:16.006  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-09 11:53:16.007  5602  5648 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-09 11:53:16.009  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-09 11:53:16.010  5602  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-09 11:53:16.012  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-09 11:53:16.012  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-09 11:53:16.012  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-09 11:53:16.012  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 11:53:16.012  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 11:53:16.012  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-09 11:53:16.013  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 11:53:16.013  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 11:53:16.013  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 11:53:16.013  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-09 11:53:16.013  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 11:53:16.013  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 11:53:16.013  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-09 11:53:16.015  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-09 11:53:16.016  5602  5648 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-09 11:53:16.016  5602  5648 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-09 11:53:16.019  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,11-09 11:53:16.019  5602  5648 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-09 11:53:16.022  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,11-09 11:53:16.022  5602  5648 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-09 11:53:16.024  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,11-09 11:53:16.025  5602  5648 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
,11-09 11:53:16.025  5602  5648 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-09 11:53:16.025  5602  5648 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-09 11:53:16.025  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-09 11:53:16.025  5602  5648 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-09 11:53:16.025  5602  5648 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-09 11:53:16.025  5602  5648 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,11-09 11:53:16.026  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-09 11:53:16.026  5602  5648 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-09 11:53:16.027  5602  5648 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-09 11:53:16.027  5602  5648 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-09 11:53:16.027  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-09 11:53:16.028  5602  5648 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,11-09 11:53:16.029  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-09 11:53:16.029  5602  5648 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-09 11:53:16.029  5602  5648 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-09 11:53:16.029  5602  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-09 11:53:16.030  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-09 11:53:16.030  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-09 11:53:16.030  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-09 11:53:16.030  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-09 11:53:16.030  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 4
11-09 11:53:16.030  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-09 11:53:16.030  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-09 11:53:16.030  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-09 11:53:16.030  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-09 11:53:16.030  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,11-09 11:53:16.030  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.032  4602  4664 D BtGatt.AdvertiseManager: message : 1
11-09 11:53:16.032  4602  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
11-09 11:53:16.039  4602  4662 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 11:53:16.039  4602  4662 D BtGatt.GattService: Client app is not null!
11-09 11:53:16.040  4602  4806 D BtGatt.GattService: unregisterClient() - clientIf=5
11-09 11:53:16.040  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-09 11:53:16.040  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.040  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-09 11:53:16.041  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:16.041  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.041  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-09 11:53:16.041  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.041  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 11:53:16.041  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:16.041  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-09 11:53:16.041  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-09 11:53:16.042  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:16.042  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.042  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.042  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.043  5602  5648 D BluetoothAdapter: STATE_ON
11-09 11:53:16.046  4602  4613 D BtGatt.GattService: registerClient() - UUID=f9b7c62b-eadf-4bfb-ba6f-4966dc288616
,11-09 11:53:16.046  4602  4662 D BtGatt.GattService: onClientRegistered() - UUID=f9b7c62b-eadf-4bfb-ba6f-4966dc288616, clientIf=5
11-09 11:53:16.047  5602  5612 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-09 11:53:16.049  4602  4664 D BtGatt.AdvertiseManager: message : 0
,11-09 11:53:16.052  4602  4664 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 11:53:16.060  4602  4662 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 11:53:16.066  4602  4662 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-09 11:53:16.066  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 11:53:16.067  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.067  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:16.067  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:16.067  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.067  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.067  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.067  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:16.067  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:16.067  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:16.067  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-09 11:53:16.067  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 11:53:16.067  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 11:53:16.067  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-09 11:53:16.067  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 11:53:16.067  5602  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-09 11:53:16.067  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-09 11:53:16.068  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-09 11:53:16.068  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:16.068  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 11:53:16.068  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-09 11:53:16.068  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:16.068  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:16.068  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:16.068  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Already started
,11-09 11:53:16.068  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-09 11:53:16.068  5602  5648 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
11-09 11:53:16.068  5602  5648 I io.jxcore.node.ConnectionHelper: start: OK
,11-09 11:53:21.075  5602  5664 E io.jxcore.node.ConnectionHelperTest: Discovery manager didn't start after 5s!
,11-09 11:53:21.079  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
11-09 11:53:21.081  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-09 11:53:21.083  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Already started
,11-09 11:53:21.084  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-09 11:53:21.084  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-09 11:53:21.088  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-09 11:53:21.090  5602  5648 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-09 11:53:21.090  5602  5648 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-09 11:53:21.090  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-09 11:53:21.091  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 11:53:21.091  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 11:53:21.091  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 11:53:21.093  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-09 11:53:21.100  5602  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-09 11:53:21.101  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-09 11:53:21.101  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-09 11:53:21.101  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-09 11:53:21.101  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-09 11:53:21.101  5602  5661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-09 11:53:21.101  5602  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-09 11:53:21.101  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-09 11:53:21.101  5602  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-09 11:53:21.101  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-09 11:53:21.101  5602  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@847751f removed from the list
11-09 11:53:21.102  5602  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-09 11:53:21.102  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-09 11:53:21.102  5602  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-09 11:53:21.102  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@116806c removed from the list
11-09 11:53:21.102  5602  5648 D io.jxcore.node.ConnectivityMonitor: stop
11-09 11:53:21.102  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-09 11:53:21.106  5602  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-09 11:53:21.107  5602  5648 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-09 11:53:21.107  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-09 11:53:21.108  5602  5648 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-09 11:53:21.108  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-09 11:53:21.108  5602  5648 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-09 11:53:21.108  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-09 11:53:21.109  5602  5648 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-09 11:53:21.110  5602  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-09 11:53:21.113  5602  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-09 11:53:21.113  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-09 11:53:21.113  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-09 11:53:21.114  5602  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-09 11:53:21.114  5602  5648 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-09 11:53:21.115  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-09 11:53:21.115  5602  5648 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-09 11:53:21.115  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-09 11:53:21.115  5602  5648 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-09 11:53:21.115  5602  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-09 11:53:21.116  5602  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,11-09 11:53:21.116  5602  5648 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-09 11:53:21.116  5602  5648 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-09 11:53:21.117  5602  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-09 11:53:21.117  5602  5648 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-09 11:53:21.118  5602  5648 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-09 11:53:21.118  5602  5648 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-09 11:53:21.118  5602  5648 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-09 11:53:21.119  5602  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-09 11:53:21.119  5602  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-09 11:53:21.119  5602  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f93656e added. We now have 3 listener(s)
,11-09 11:53:21.121  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:21.121  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-09 11:53:21.121  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-09 11:53:21.121  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-09 11:53:21.121  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbde40f added. We now have 3 listener(s)
,11-09 11:53:21.121  5602  5648 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-09 11:53:21.122  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-09 11:53:21.125  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 11:53:21.129  5602  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 11:53:21.129  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:21.129  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:21.129  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:21.129  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:21.129  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:21.129  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:53:21.129  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 11:53:21.131  5602  5648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 11:53:21.131  5602  5648 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-09 11:53:21.133  5602  5648 D BluetoothAdapter: enable(): BT is already enabled..!
,11-09 11:53:21.133   926  5098 D WifiService: setWifiEnabled: true pid=5602, uid=10077
11-09 11:53:21.133   926  5098 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-09 11:53:21.135  5602  5648 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
11-09 11:53:21.136  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:21.139  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:21.139  5602  5648 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-09 11:53:21.140  5602  5648 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-09 11:53:21.142   926  3092 D WifiService: setWifiEnabled: false pid=5602, uid=10077
11-09 11:53:21.142   926  3092 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 11:53:21.144   926  2950 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-09 11:53:21.145   926  2950 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-09 11:53:21.145   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-09 11:53:21.145   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 11:53:21.152   926  5354 D DhcpClient: Clearing IP address
,11-09 11:53:21.152   507   919 D CommandListener: Clearing all IP addresses on wlan0
,11-09 11:53:21.159   507   919 D CommandListener: Setting iface cfg
,11-09 11:53:21.162  3529  5405 V NativeCrypto: Read error: ssl=0x7f91086880: I/O error during system call, Connection timed out
,11-09 11:53:21.164  3529  5405 V NativeCrypto: SSL shutdown failed: ssl=0x7f91086880: I/O error during system call, Broken pipe
11-09 11:53:21.166   926  3367 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-09 11:53:21.166   926  5352 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-09 11:53:21.168   926  5355 D DhcpClient: Receive thread stopped
11-09 11:53:21.169   926  5352 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-09 11:53:21.169   926  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-09 11:53:21.169   926  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-09 11:53:21.170   926  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-09 11:53:21.174   926  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-09 11:53:21.174   926  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-09 11:53:21.178   533   533 E Parcel  : Reading a NULL string not supported here.
,11-09 11:53:21.180   926   926 D RttService: SCAN_AVAILABLE : 1
11-09 11:53:21.181   926  3019 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-09 11:53:21.184   926  2954 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-09 11:53:21.185  3708  3826 W QCNEJ   : |CORE| network lost: 100
11-09 11:53:21.186  3708  3826 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-09 11:53:21.197   926  2950 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-09 11:53:21.209   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-09 11:53:21.218   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 11:53:21.238   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 11:53:21.238   507   919 D CommandListener: Clearing all IP addresses on wlan0
11-09 11:53:21.239   926  2954 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-09 11:53:21.239   926  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-09 11:53:21.241   926  2950 D DhcpClient: doQuit
,11-09 11:53:21.241   926  2950 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-09 11:53:21.242  3424  3424 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-09 11:53:21.243   926   944 D Tethering: MasterInitialState.processMessage what=3
11-09 11:53:21.243   926  5354 D DhcpClient: onQuitting
11-09 11:53:21.245  5248  5248 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f24eda1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-09 11:53:21.247  3908  3908 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-09 11:53:21.248  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:21.248  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:21.248  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:21.248  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 11:53:21.248  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:21.248  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:21.248  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:21.248  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 11:53:21.250  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-09 11:53:21.253  3922  3922 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-09 11:53:21.256  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:21.256  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:21.256  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:21.256  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 11:53:21.256  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:21.256  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:21.256  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:21.256  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 11:53:21.258  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-09 11:53:21.259  3922  3922 D SystemUpdateService: onCreate
,11-09 11:53:21.263  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:21.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:21.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:21.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 11:53:21.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:21.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:21.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:21.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 11:53:21.265  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-09 11:53:21.267  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:21.268  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:21.268  3424  3424 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-09 11:53:21.269  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:21.271  3424  3424 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-09 11:53:21.272  3922  3922 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-09 11:53:21.279  3922  5674 I SystemUpdateService: active receiver: enabled
,11-09 11:53:21.280  3922  3922 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-09 11:53:21.285  3922  4269 I iu.UploadsManager: num queued entries: 0
,11-09 11:53:21.285  3922  4269 I iu.UploadsManager: num updated entries: 0
,11-09 11:53:21.286  3922  4269 I iu.SyncManager: NEXT; no task
11-09 11:53:21.288  3922  3922 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-09 11:53:21.289  3922  3922 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-09 11:53:21.293  5379  5379 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-09 11:53:21.296  5379  5379 D SprintDMHelper: simOperator: 
11-09 11:53:21.296  5379  5379 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-09 11:53:21.298  3922  5674 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-09 11:53:21.301   507   919 E Netd    : netlink response contains error (No such file or directory)
,11-09 11:53:21.303   926  2954 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-09 11:53:21.306  3922  5674 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-09 11:53:21.306  3922  5674 I SystemUpdateService: now status is 0 (complete)
,11-09 11:53:21.306  3922  5674 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-09 11:53:21.308  3922  5674 I SystemUpdateService: file has been verified
11-09 11:53:21.308  3922  5674 I SystemUpdateService: OTA package size = 21989297
,11-09 11:53:21.315  3424  3424 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-09 11:53:21.316  3922  5674 I SystemUpdateService: showing system update notification
,11-09 11:53:21.321   926  3092 I ActivityManager: Start proc 5680:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-09 11:53:21.325  3424  3424 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-09 11:53:21.331   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-09 11:53:21.333  3922  3922 D SystemUpdateService: onDestroy
,11-09 11:53:21.362  5680  5680 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-09 11:53:21.369   926   937 I ActivityManager: Killing 4966:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-09 11:53:21.426   926  2950 D wifi    : In wifi stop Hal
,11-09 11:53:21.426  4396  4396 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-09 11:53:21.426   926  2950 D wifi    : halHandle = 0x7f8ee1eb80, mVM = 0x7fab44d140, mCls = 0x100a02
11-09 11:53:21.426   926  3423 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-09 11:53:21.427   926  3423 D WifiHAL : Got a signal to exit!!!
11-09 11:53:21.427   926  3423 I WifiHAL : Exit wifi_event_loop
11-09 11:53:21.428  4063  4176 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-09 11:53:21.428   926  2950 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-09 11:53:21.428   926  2950 E WifiHAL : Event processing terminated
11-09 11:53:21.429   926  2950 D wifi    : In wifi cleaned up handler
11-09 11:53:21.429   926  2950 I WifiHAL : Internal cleanup completed
11-09 11:53:21.430  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:21.433  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:21.434  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:21.450   926  3423 D wifi    : set interface wlan0 flags (DOWN)
,11-09 11:53:21.451   926  2950 D WifiNative-HAL: HAL event thread stopped successfully
,11-09 11:53:21.510   507   919 E Netd    : netlink response contains error (No such file or directory)
,11-09 11:53:21.648  5602  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:21.652   926  5098 D WifiService: setWifiEnabled: true pid=5602, uid=10077
,11-09 11:53:21.653   926  5098 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 11:53:21.660   507   919 D SoftapController: Softap fwReload - Ok
,11-09 11:53:21.660   926   944 D Tethering: InitialState.processMessage what=4
,11-09 11:53:21.666   507   919 D CommandListener: Setting iface cfg
,11-09 11:53:21.667   507   919 D CommandListener: Trying to bring down wlan0
,11-09 11:53:21.668   507   919 D CommandListener: Clearing all IP addresses on wlan0
,11-09 11:53:21.670   926   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
11-09 11:53:21.673   926  2950 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-09 11:53:22.159   926  3092 D WifiService: setWifiEnabled: true pid=5602, uid=10077
,11-09 11:53:22.162   926  3092 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 11:53:22.275   926  2950 D wifi    : set interface wlan0 flags (UP)
,11-09 11:53:22.277   926  2950 I WifiHAL : Initializing wifi
,11-09 11:53:22.277   926  2950 I WifiHAL : Creating socket
,11-09 11:53:22.284   926   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-09 11:53:22.288   926  2950 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-09 11:53:22.289   926  2950 D wifi    : Did set static halHandle = 0x7f8ee1eb80
,11-09 11:53:22.289   926  2950 D wifi    : halHandle = 0x7f8ee1eb80, mVM = 0x7fab44d140, mCls = 0x17ea
11-09 11:53:22.289   926  2950 D wifi    : array field set
,11-09 11:53:22.289   926  2950 I WifiNative-HAL: interface[0] = wlan0
11-09 11:53:22.292   926  5702 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547858017152
,11-09 11:53:22.293   926  5702 D wifi    : waitForHalEvents called, vm = 0x7fab44d140, obj = 0x17ea, env = 0x7f935be680
,11-09 11:53:22.362  5703  5703 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-09 11:53:22.392   926  2950 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-09 11:53:22.393   926  2950 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-09 11:53:22.396  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:22.398  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:22.400  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:22.435  5703  5703 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-09 11:53:22.452  5703  5703 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-09 11:53:22.452  5703  5703 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-09 11:53:22.665   926  3368 D WifiService: setWifiEnabled: true pid=5602, uid=10077
,11-09 11:53:22.665   926  3368 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 11:53:23.169   926  3367 D WifiService: setWifiEnabled: true pid=5602, uid=10077
,11-09 11:53:23.169   926  3367 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 11:53:23.410   926  2950 D WifiConfigStore: Loading config and enabling all networks 
11-09 11:53:23.421  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:23.421  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:23.421  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:23.421  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:23.421  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:23.421  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:23.421  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:23.421  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 11:53:23.426  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:23.433  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:23.433  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:23.433  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:23.433  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:23.433  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:23.433  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:23.433  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:23.433  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 11:53:23.439  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:23.445  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:23.445  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:23.445  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:23.445  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:23.445  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:23.445  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:23.445  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:23.445  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:23.448  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:23.457   926  2950 D WifiConfigStore: loaded 0 passpoint configs
,11-09 11:53:23.458   926  2950 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-09 11:53:23.459   926  2950 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-09 11:53:23.460   926  2950 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-09 11:53:23.461   926  2950 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-09 11:53:23.462   926  2950 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-09 11:53:23.463   926  2950 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-09 11:53:23.463   926  2950 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-09 11:53:23.463   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-09 11:53:23.463   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-09 11:53:23.463   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-09 11:53:23.464   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-09 11:53:23.464   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-09 11:53:23.468   926  2950 D WifiNative-HAL: Setting external_sim to 1
,11-09 11:53:23.468  4396  4396 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-09 11:53:23.468   926  2950 D wifi    : setting dfs flag to true, 0x7f9577db20
,11-09 11:53:23.469   926  2950 D WifiStateMachine: Setting OUI to DA-A1-19
11-09 11:53:23.469   926  2950 D wifi    : setting scan oui 0x7f9577db20
11-09 11:53:23.470   926  2950 D WifiHAL : Sending mac address OUI
,11-09 11:53:23.474   926  2950 E native  : do suspend false
,11-09 11:53:23.482   926  2950 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-09 11:53:23.482   926   926 D RttService: SCAN_AVAILABLE : 3
11-09 11:53:23.482   507   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-09 11:53:23.483   926  3019 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-09 11:53:23.484   507   919 D CommandListener: Setting iface cfg
,11-09 11:53:23.489   926  2949 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
,11-09 11:53:23.489   926  2949 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-09 11:53:23.501   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=104207 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-09 11:53:23.502   926  2949 D WifiNative-HAL: p2pGetDeviceAddress
11-09 11:53:23.503   926  2949 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-09 11:53:23.675  5602  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:23.687  4602  4658 D BluetoothAdapterState: Current state: ON, message: 23
,11-09 11:53:23.687  4602  4658 D BluetoothAdapterProperties: Setting state to 13
,11-09 11:53:23.687  4602  4658 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-09 11:53:23.690  4602  4658 D BluetoothAdapterProperties: onBluetoothDisable()
11-09 11:53:23.693  4602  4658 I BluetoothAdapterState: Entering PendingCommandState
11-09 11:53:23.694  4602  4602 D BluetoothMapService: onReceive
11-09 11:53:23.694  4602  4602 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-09 11:53:23.694  4602  4602 D BluetoothMapService: STATE_TURNING_OFF
11-09 11:53:23.695  4602  4602 D BluetoothMapService: MAP Service closeService in
,11-09 11:53:23.695  4602  4602 D BluetoothMapMasInstance0: MAP Service shutdown
11-09 11:53:23.695  4602  4602 D ObexServerSockets0: shutdown(block = true)
11-09 11:53:23.697  4602  4602 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-09 11:53:23.697  4602  4809 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-09 11:53:23.698  4602  4796 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-09 11:53:23.698  4602  4602 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-09 11:53:23.699  4602  4810 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-09 11:53:23.710  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-09 11:53:23.710  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:23.710  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:23.710  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:23.710  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:23.710  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 11:53:23.710  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:23.710  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:23.710  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:23.711  4602  4602 I BtOppRfcommListener: stopping Accept Thread
11-09 11:53:23.711  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:23.712  4602  5307 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-09 11:53:23.712  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-09 11:53:23.712  4602  5307 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-09 11:53:23.714  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:23.715  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:23.715  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:23.715  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:23.715  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:23.715  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 11:53:23.715  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:23.715  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:23.715  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:23.715  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:23.716  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:23.716  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 13
11-09 11:53:23.718  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:23.719  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:23.719  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:23.719  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:23.719  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:23.719  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 11:53:23.719  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:23.719  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:23.719  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:23.720  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:23.720  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:23.725   926   939 I ActivityManager: Start proc 5716:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-09 11:53:23.726  4602  4662 D BluetoothAdapterProperties: Scan Mode:20
11-09 11:53:23.726  4602  4658 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-09 11:53:23.728  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:23.729  4602  4602 D HeadsetService: Received stop request...Stopping profile...
,11-09 11:53:23.731  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:23.732  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
,11-09 11:53:23.732  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:23.734   926   926 D BluetoothHeadset: Proxy object disconnected
,11-09 11:53:23.735  3754  3778 D BluetoothHeadset: Proxy object disconnected
11-09 11:53:23.736  4602  4602 D A2dpService: Received stop request...Stopping profile...
11-09 11:53:23.736   926   926 D BluetoothHeadset: Proxy object disconnected
11-09 11:53:23.736  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.736  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 11:53:23.736  4602  4801 D A2dpStateMachine: Exit Disconnected: -1
11-09 11:53:23.736  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.737  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.737  3052  3935 D BluetoothHeadset: Proxy object disconnected
11-09 11:53:23.738  3052  3052 D HeadsetProfile: Bluetooth service disconnected
11-09 11:53:23.737   926   926 D BluetoothHeadset: Proxy object disconnected
11-09 11:53:23.738   926   926 D BluetoothA2dp: Proxy object disconnected
11-09 11:53:23.738  3052  3052 D BluetoothA2dp: Proxy object disconnected
11-09 11:53:23.739  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:23.739  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 11:53:23.739  4602  4602 D HidService: Received stop request...Stopping profile...
11-09 11:53:23.739  4602  4602 D HidService: Stopping Bluetooth HidService
11-09 11:53:23.741  3052  3052 D BluetoothInputDevice: Proxy object disconnected
11-09 11:53:23.741  3052  3052 D HidProfile: Bluetooth service disconnected
11-09 11:53:23.741  4602  4602 D HealthService: Received stop request...Stopping profile...
11-09 11:53:23.742  4602  4602 D PanService: Received stop request...Stopping profile...
11-09 11:53:23.744  3052  3052 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-09 11:53:23.744  3052  3052 D PanProfile: Bluetooth service disconnected
11-09 11:53:23.744  4602  4602 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:23.744  4602  4602 V BluetoothAdapterState: isTurningOn()=false
,11-09 11:53:23.744  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:23.744  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:23.746  4602  4602 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-09 11:53:23.746  4602  4602 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-09 11:53:23.746  4602  4602 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:23.746  4602  4782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 11:53:23.746  4602  4602 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:23.746  4602  4782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 11:53:23.746  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:23.746  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:23.746  4602  4782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 11:53:23.747  4602  4662 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-09 11:53:23.747  4602  4602 D BluetoothMapService: Received stop request...Stopping profile...
11-09 11:53:23.747  4602  4602 D BluetoothMapService: stop()
11-09 11:53:23.747  4602  4662 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-09 11:53:23.747  4602  4602 D BluetoothMapAppObserver: deinitObservers()
11-09 11:53:23.748  4602  4602 D BluetoothMapAppObserver: removeReceiver()
11-09 11:53:23.749  3052  3052 D BluetoothMap: Proxy object disconnected
11-09 11:53:23.749  3052  3052 D MapProfile: Bluetooth service disconnected
11-09 11:53:23.751  4602  4782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 11:53:23.752  4602  4782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 11:53:23.752  4602  4662 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-09 11:53:23.752  4602  4782 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-09 11:53:23.752  4602  4782 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-09 11:53:23.752  4602  4782 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-09 11:53:23.752  4602  4782 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-09 11:53:23.755  4602  4602 D SapService: Received stop request...Stopping profile...
11-09 11:53:23.755  4602  4602 V SapService: stop()
11-09 11:53:23.758  4602  4602 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:23.758  4602  4602 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:23.758  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:23.758  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:23.758  4602  4602 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-09 11:53:23.758  4602  4602 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-09 11:53:23.758  4602  4662 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-09 11:53:23.759  4602  4602 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:23.759  4602  4602 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:23.759  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:23.759  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:23.759  4602  4602 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-09 11:53:23.759  4602  4662 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-09 11:53:23.759  4602  4602 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-09 11:53:23.760  4602  4602 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:23.760  4602  4602 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:23.760  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:23.760  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:23.760  4602  4602 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-09 11:53:23.761  4602  4602 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-09 11:53:23.762  4602  4602 D BluetoothMapService: MAP Service closeService in
11-09 11:53:23.762  4602  4602 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:23.762  4602  4602 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:23.762  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:23.762  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:23.762  4602  4602 D BluetoothMapService: cleanup()
11-09 11:53:23.763  4602  4602 D BluetoothMapService: MAP Service closeService in
11-09 11:53:23.763  4602  4602 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:23.763  4602  4602 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:23.763  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:23.763  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:23.763  4602  4658 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-09 11:53:23.763  4602  4658 D BluetoothAdapterProperties: Setting state to 15
11-09 11:53:23.763  4602  4658 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-09 11:53:23.764  4602  4658 I BluetoothAdapterState: Entering BleOnState
11-09 11:53:23.764  3052  3065 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-09 11:53:23.765   926   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-09 11:53:23.765  3754  3779 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 11:53:23.766  3052  3067 D BluetoothPan: onBluetoothStateChange on: false
11-09 11:53:23.766   926   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 11:53:23.766  3052  3935 D BluetoothPbap: onBluetoothStateChange: up=false
11-09 11:53:23.768  3052  3065 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 11:53:23.768   926   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 11:53:23.768  3052  3067 D BluetoothMap: onBluetoothStateChange: up=false
11-09 11:53:23.769   926   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 11:53:23.769  3052  3935 D BluetoothA2dp: onBluetoothStateChange: up=false
11-09 11:53:23.770  4602  4658 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-09 11:53:23.770  4602  4658 D BluetoothAdapterProperties: Setting state to 16
11-09 11:53:23.770  4602  4658 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-09 11:53:23.770  5716  5716 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-09 11:53:23.773  4602  4658 D BluetoothAdapterProperties: onBleDisable
11-09 11:53:23.773  4602  4658 I BluetoothAdapterState: Entering PendingCommandState
11-09 11:53:23.774  4602  4659 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-09 11:53:23.774  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:23.775  4602  4662 D BluetoothAdapterProperties: Scan Mode:20
11-09 11:53:23.778  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:23.778  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 10
11-09 11:53:23.778  5602  5602 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: Bluetooth disabled, pausing BLE based peer discovery...
11-09 11:53:23.778  4602  4782 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-09 11:53:23.778  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.778  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.778  4602  4782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 11:53:23.779  5602  5602 D BluetoothAdapter: STATE_OFF
,11-09 11:53:23.785  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: BT Adapter is not turned ON
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: java.lang.IllegalStateException: BT Adapter is not turned ON
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.bluetooth.le.BluetoothLeUtils.checkAdapterStateOn(BluetoothLeUtils.java:136)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.bluetooth.le.BluetoothLeScanner.stopScan(BluetoothLeScanner.java:169)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner.stop(BleScanner.java:150)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stopScanner(BlePeerDiscoverer.java:436)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stopScannerAndAdvertiser(BlePeerDiscoverer.java:503)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.stopBlePeerDiscoverer(DiscoveryManager.java:1217)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.onBluetoothAdapterStateChanged(DiscoveryManager.java:773)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver.onReceive(BluetoothManager.java:564)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:53:23.790  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 11:53:23.791  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:23.791  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.791  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-09 11:53:23.791  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
,11-09 11:53:23.791  4602  4664 D BtGatt.AdvertiseManager: message : 1
11-09 11:53:23.792   926   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@716b685:true
11-09 11:53:23.792  4602  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
11-09 11:53:23.792  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-09 11:53:23.800  4602  4662 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 11:53:23.800  4602  4662 D BtGatt.GattService: Client app is not null!
,11-09 11:53:23.801  4602  4807 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-09 11:53:23.801  4602  4782 E bt_btif : bta_gattc_deregister Deregister Failedm unknown client cif
11-09 11:53:23.801  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 11:53:23.802  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:23.802  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-09 11:53:23.802  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.802  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:23.802  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.802  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-09 11:53:23.802  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-09 11:53:23.802  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.802  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.802  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-09 11:53:23.802  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.804  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.804  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
11-09 11:53:23.804  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.804  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.804  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-09 11:53:23.804  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:23.804  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.804  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-09 11:53:23.804  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:23.805  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.806  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-09 11:53:23.806  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.807  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:23.808  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:23.810  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:23.810  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-09 11:53:23.810  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.811  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-09 11:53:23.811  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.811  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:23.812  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:23.813  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,11-09 11:53:23.817   926  3914 I ActivityManager: Start proc 5729:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-09 11:53:23.837  5716  5716 D LocalBluetoothProfileManager: Adding local MAP profile
,11-09 11:53:23.839  5716  5716 D BluetoothMap: Create BluetoothMap proxy object
,11-09 11:53:23.846  5729  5729 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-09 11:53:23.851  5716  5716 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-09 11:53:23.867  5716  5716 D DockEventReceiver: finishStartingService: stopping service
,11-09 11:53:23.875   926   936 I ActivityManager: Killing 5248:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-09 11:53:23.985  4602  4662 I bt_hci  : shut_down
,11-09 11:53:23.990  4602  4666 D bt_hwcfg: hw_epilog_process
,11-09 11:53:23.990  4602  4666 I bt_vendor: low_power_mode_cb
,11-09 11:53:23.993  4602  4666 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-09 11:53:23.993  4602  4666 I bt_vendor: epilog_cb
11-09 11:53:23.993  4602  4666 I bt_hci  : epilog_finished_callback
,11-09 11:53:23.996  4602  4662 I bt_hci_h4: hal_close
,11-09 11:53:23.996  4602  4662 I bt_userial_vendor: device fd = 54 close
,11-09 11:53:24.084  5729  5729 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.io.File.exists(File.java:361)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-09 11:53:24.084  5729  5729 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 11:53:24.084  5729  5729 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 11:53:24.084  5729  5729 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.e.b(PG:170)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 11:53:24.084  5729  5729 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.k.d(PG:583)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.e.b(PG:170)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:53:24.084  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 11:53:24.085  5729  5729 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at java.io.File.exists(File.java:361)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 11:53:24.085  5729  5729 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at java.io.File.exists(File.java:361)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 11:53:24.085  5729  5729 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:53:24.085  5729  5729 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 11:53:24.088  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-09 11:53:24.094  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-09 11:53:24.099  5716  5716 D DockEventReceiver: finishStartingService: stopping service
11-09 11:53:24.102   926  3092 I ActivityManager: Killing 5441:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-09 11:53:24.142  4602  4659 D bt_stack_manager: event_shut_down_stack finished.
11-09 11:53:24.143  4602  4658 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-09 11:53:24.144  4602  4658 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-09 11:53:24.144  4602  4602 D BtGatt.DebugUtils: handleDebugAction() action=null
11-09 11:53:24.145  4602  4602 D BtGatt.GattService: Received stop request...Stopping profile...
11-09 11:53:24.145  4602  4602 D BtGatt.GattService: stop()
11-09 11:53:24.145  4602  4602 D BtGatt.AdvertiseManager: advertise clients cleared
11-09 11:53:24.147  4602  4602 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:24.148  4602  4602 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:24.148  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:24.148  4602  4602 V BluetoothAdapterState: isBleTurningOff()=true
11-09 11:53:24.148  4602  4658 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-09 11:53:24.148  4602  4658 D BluetoothAdapterProperties: Setting state to 10
11-09 11:53:24.148  4602  4658 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-09 11:53:24.149  4602  4658 I BluetoothAdapterState: Entering OffState
11-09 11:53:24.150   926   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-09 11:53:24.155  4602  4602 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-09 11:53:24.156  4602  4602 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-09 11:53:24.156  4602  4602 I BluetoothServiceJni: cleanupNative: return from cleanup
11-09 11:53:24.157  4602  4659 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-09 11:53:24.165  4602  4602 I art     : System.exit called, status: 0
11-09 11:53:24.166  4602  4602 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-09 11:53:24.185  5602  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:24.187   382   382 E lowmemorykiller: Error writing /proc/4602/oom_score_adj; errno=22
,11-09 11:53:24.208   926  3092 I ActivityManager: Process com.android.bluetooth (pid 4602) has died
,11-09 11:53:24.209   926  3092 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,11-09 11:53:24.299  5729  5749 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-09 11:53:24.313  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-09 11:53:24.316   926   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@653d6e2:true
,11-09 11:53:25.243   926   939 I ActivityManager: Start proc 5765:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-09 11:53:25.330  5765  5765 D AdapterServiceConfig: Adding HeadsetService
,11-09 11:53:25.330  5765  5765 D AdapterServiceConfig: Adding A2dpService
11-09 11:53:25.331  5765  5765 D AdapterServiceConfig: Adding HidService
11-09 11:53:25.331  5765  5765 D AdapterServiceConfig: Adding HealthService
11-09 11:53:25.331  5765  5765 D AdapterServiceConfig: Adding PanService
,11-09 11:53:25.331  5765  5765 D AdapterServiceConfig: Adding GattService
11-09 11:53:25.331  5765  5765 D AdapterServiceConfig: Adding BluetoothMapService
11-09 11:53:25.331  5765  5765 D AdapterServiceConfig: Adding SapService
,11-09 11:53:25.344   926   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@535603a:true
,11-09 11:53:25.344  5765  5765 D BluetoothAdapterState: make() - Creating AdapterState
,11-09 11:53:25.347  5765  5765 I bt_bluedroid: init
,11-09 11:53:25.347  5765  5777 I BluetoothAdapterState: Entering OffState
,11-09 11:53:25.349  5765  5778 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-09 11:53:25.349  5765  5778 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-09 11:53:25.349  5765  5778 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-09 11:53:25.349  5765  5778 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-09 11:53:25.349  5765  5765 I bt_bluedroid: get_profile_interface socket
,11-09 11:53:25.351  5765  5781 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-09 11:53:25.352  5765  5765 I bt_bluedroid: get_profile_interface sdp
11-09 11:53:25.352  5765  5781 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-09 11:53:25.356  5765  5776 I bt_bluedroid: config_hci_snoop_log
,11-09 11:53:25.357   926   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-09 11:53:25.361  5765  5777 D BluetoothAdapterState: Current state: OFF, message: 0
,11-09 11:53:25.361  5765  5777 D BluetoothAdapterProperties: Setting state to 14
11-09 11:53:25.361  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-09 11:53:25.363  5765  5777 D BluetoothBondStateMachine: make
,11-09 11:53:25.365  5765  5782 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-09 11:53:25.367  5765  5777 I BluetoothAdapterState: Entering PendingCommandState
,11-09 11:53:25.368  5765  5765 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-09 11:53:25.370  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
11-09 11:53:25.371  5765  5765 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-09 11:53:25.371  5765  5765 D BtGatt.GattService: Received start request. Starting profile...
11-09 11:53:25.371  5765  5765 D BtGatt.GattService: start()
11-09 11:53:25.372  5765  5765 I bt_bluedroid: get_profile_interface gatt
,11-09 11:53:25.372  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:25.372  5765  5765 D BtGatt.AdvertiseManager: advertise manager created
,11-09 11:53:25.377  5765  5765 V BluetoothAdapterState: isTurningOff()=false
,11-09 11:53:25.377  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:25.377  5765  5765 V BluetoothAdapterState: isBleTurningOn()=true
11-09 11:53:25.377  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:25.377  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-09 11:53:25.379  5765  5777 I bt_bluedroid: bt_bluedroid
11-09 11:53:25.379  5765  5778 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-09 11:53:25.379  5765  5778 I bt_hci  : start_up
,11-09 11:53:25.384  5765  5778 I bt_vendor: alloc value 0xf3dbb871
11-09 11:53:25.384  5765  5778 I bt_vendor: init
11-09 11:53:25.384  5765  5778 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-09 11:53:25.384  5765  5778 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-09 11:53:25.497  5765  5778 D bt_hci  : start_up starting async portion
,11-09 11:53:25.498  5765  5785 I bt_hci  : event_finish_startup
11-09 11:53:25.498  5765  5785 I bt_hci_h4: hal_open
11-09 11:53:25.498  5765  5785 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-09 11:53:25.502  5765  5785 I bt_userial_vendor: device fd = 54 open
,11-09 11:53:25.497  5786  5786 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-09 11:53:25.515  5765  5785 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-09 11:53:25.518  5765  5785 D bt_hwcfg: Chipset BCM4358A3
,11-09 11:53:25.518  5765  5785 D bt_hwcfg: Target name = [BCM4358A3]
11-09 11:53:25.518  5765  5785 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-09 11:53:25.696  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-09 11:53:25.913  5765  5785 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-09 11:53:25.913  5765  5785 D bt_hwcfg: Settlement delay -- 100 ms
,11-09 11:53:25.913  5765  5785 I bt_hwcfg: Setting fw settlement delay to 100 
,11-09 11:53:26.037  5765  5785 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-09 11:53:26.038  5765  5785 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-09 11:53:26.040  5765  5785 I bt_hwcfg: vendor lib fwcfg completed
,11-09 11:53:26.040  5765  5785 I bt_vendor: firmware callback
11-09 11:53:26.040  5765  5785 I bt_hci  : firmware_config_callback
,11-09 11:53:26.049  5765  5788 I bt_btu  : btu_task pending for preload complete event
,11-09 11:53:26.049  5765  5788 I bt_btu_task: Bluetooth chip preload is complete
11-09 11:53:26.049  5765  5788 I bt_btu  : btu_task received preload complete event
,11-09 11:53:26.055  5765  5788 I         : BTE_InitTraceLevels -- TRC_HCI
,11-09 11:53:26.056  5765  5788 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-09 11:53:26.056  5765  5788 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-09 11:53:26.056  5765  5788 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-09 11:53:26.056  5765  5788 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-09 11:53:26.056  5765  5788 I         : BTE_InitTraceLevels -- TRC_A2D
,11-09 11:53:26.056  5765  5788 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-09 11:53:26.056  5765  5788 I         : BTE_InitTraceLevels -- TRC_BTM
11-09 11:53:26.056  5765  5788 I         : BTE_InitTraceLevels -- TRC_GAP
11-09 11:53:26.057  5765  5788 I         : BTE_InitTraceLevels -- TRC_PAN
11-09 11:53:26.057  5765  5788 I         : BTE_InitTraceLevels -- TRC_SDP
,11-09 11:53:26.057  5765  5788 I         : BTE_InitTraceLevels -- TRC_GATT
11-09 11:53:26.057  5765  5788 I         : BTE_InitTraceLevels -- TRC_SMP
11-09 11:53:26.057  5765  5788 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-09 11:53:26.057  5765  5788 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-09 11:53:26.137  5765  5788 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d39549
,11-09 11:53:26.137  5765  5788 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d39549 
,11-09 11:53:26.149  5765  5781 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-09 11:53:26.151  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-09 11:53:26.151  5765  5781 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-09 11:53:26.153  5765  5781 D BluetoothAdapterProperties: Name is: Nexus 6P
11-09 11:53:26.156  5765  5781 D BluetoothAdapterProperties: Scan Mode:20
11-09 11:53:26.156  5765  5781 D BluetoothAdapterProperties: Discoverable Timeout:120
11-09 11:53:26.156  5765  5781 D bt_hci  : do_postload posting postload work item
11-09 11:53:26.156  5765  5785 I bt_hci  : event_postload
11-09 11:53:26.157  5765  5785 I bt_vendor: sco_config_cb
,11-09 11:53:26.157  5765  5785 I bt_hci  : sco_config_callback postload finished.
11-09 11:53:26.161  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:26.165  5765  5781 D bt_bte_conf: Device ID record 1 : primary
,11-09 11:53:26.165  5765  5781 D bt_bte_conf:   vendorId            = 000f
,11-09 11:53:26.165  5765  5781 D bt_bte_conf:   vendorIdSource      = 0001
,11-09 11:53:26.165  5765  5781 D bt_bte_conf:   product             = 1200
11-09 11:53:26.165  5765  5781 D bt_bte_conf:   version             = 1436
11-09 11:53:26.165  5765  5781 D bt_bte_conf:   clientExecutableURL = 
11-09 11:53:26.165  5765  5781 D bt_bte_conf:   serviceDescription  = 
11-09 11:53:26.165  5765  5781 D bt_bte_conf:   documentationURL    = 
,11-09 11:53:26.166  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:26.166  5765  5781 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-09 11:53:26.166  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-09 11:53:26.166  5765  5778 D bt_stack_manager: event_start_up_stack finished
,11-09 11:53:26.166  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.166  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-09 11:53:26.167  5765  5777 D BluetoothAdapterProperties: Setting state to 15
11-09 11:53:26.167  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-09 11:53:26.171  5765  5777 I BluetoothAdapterState: Entering BleOnState
11-09 11:53:26.172  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.172  5765  5785 I bt_vendor: low_power_mode_cb
11-09 11:53:26.172  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.172  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.175  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:26.175  5765  5777 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-09 11:53:26.175  5765  5777 D BluetoothAdapterProperties: Setting state to 11
11-09 11:53:26.175  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-09 11:53:26.180  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:26.181  5765  5765 D HeadsetService: Received start request. Starting profile...
11-09 11:53:26.183  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:26.184  5765  5765 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-09 11:53:26.184  5765  5765 D HeadsetStateMachine: make
11-09 11:53:26.185  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:26.186  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 11
,11-09 11:53:26.187  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:26.195  5765  5765 D HeadsetStateMachine: max_hf_connections = 1
,11-09 11:53:26.195  5765  5765 I bt_bluedroid: get_profile_interface handsfree
11-09 11:53:26.196  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-09 11:53:26.196  5765  5781 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
,11-09 11:53:26.202  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:26.203  5765  5765 D A2dpService: Received start request. Starting profile...
,11-09 11:53:26.204  5765  5765 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-09 11:53:26.204  5765  5765 I bt_bluedroid: get_profile_interface avrcp
11-09 11:53:26.205  5765  5777 I BluetoothAdapterState: Entering PendingCommandState
11-09 11:53:26.205  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-09 11:53:26.210  5765  5765 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-09 11:53:26.210  5765  5765 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-09 11:53:26.210  5765  5765 D A2dpStateMachine: make
,11-09 11:53:26.211  5765  5765 I bt_bluedroid: get_profile_interface a2dp
,11-09 11:53:26.212  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-09 11:53:26.213  5765  5797 D A2dpStateMachine: Enter Disconnected: -2
,11-09 11:53:26.215  5765  5765 I BluetoothHidServiceJni: classInitNative: succeeds
11-09 11:53:26.216  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:26.217  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-09 11:53:26.218  5765  5765 D HidService: Received start request. Starting profile...
11-09 11:53:26.218  5765  5765 I bt_bluedroid: get_profile_interface hidhost
11-09 11:53:26.218  5716  5716 D BluetoothInputDevice: Proxy object connected
11-09 11:53:26.218  5765  5765 D HidService: setHidService(): set to: null
11-09 11:53:26.218  5765  5781 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d1a56d
11-09 11:53:26.218  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-09 11:53:26.219  5716  5716 D HidProfile: Bluetooth service connected
11-09 11:53:26.220  5765  5765 I BluetoothHealthServiceJni: classInitNative: succeeds
11-09 11:53:26.221  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:26.222  5765  5765 D HealthService: Received start request. Starting profile...
,11-09 11:53:26.224  5765  5765 I bt_bluedroid: get_profile_interface health
,11-09 11:53:26.225  5765  5765 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-09 11:53:26.226  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
11-09 11:53:26.227  5716  5716 D BluetoothPan: BluetoothPAN Proxy object connected
11-09 11:53:26.227  5765  5765 D PanService: Received start request. Starting profile...
,11-09 11:53:26.227  5765  5765 D BluetoothPanServiceJni: initializeNative(L110): pan
11-09 11:53:26.227  5765  5765 I bt_bluedroid: get_profile_interface pan
11-09 11:53:26.227  5716  5716 D PanProfile: Bluetooth service connected
11-09 11:53:26.228  5765  5781 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-09 11:53:26.228  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:26.228  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:26.228  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.228  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:26.229  5765  5794 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-09 11:53:26.230  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:26.231  5716  5716 D BluetoothMap: Proxy object connected
11-09 11:53:26.231  5765  5765 D BluetoothMapService: Received start request. Starting profile...
11-09 11:53:26.231  5765  5765 D BluetoothMapService: start()
,11-09 11:53:26.232  5716  5716 D MapProfile: Bluetooth service connected
11-09 11:53:26.232  5716  5716 D BluetoothMap: getConnectedDevices()
11-09 11:53:26.233  5716  5716 D BluetoothMap: Bluetooth is Not enabled
,11-09 11:53:26.235  5765  5765 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-09 11:53:26.235  5765  5765 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-09 11:53:26.235  5765  5765 D BluetoothMapAppObserver: createReceiver()
11-09 11:53:26.237  5765  5765 D BluetoothMapAppObserver: initObservers()
11-09 11:53:26.237  5765  5765 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-09 11:53:26.243  5765  5765 V SapService: SapBinder()
,11-09 11:53:26.243  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:26.244  5765  5765 D SapService: Received start request. Starting profile...
11-09 11:53:26.244  5765  5765 V SapService: start()
,11-09 11:53:26.246  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:26.246  5765  5765 V BluetoothAdapterState: isTurningOn()=true
,11-09 11:53:26.246  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.246  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:26.246  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:26.246  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:26.246  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.246  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
,11-09 11:53:26.247  5765  5765 V BluetoothAdapterState: isTurningOff()=false
,11-09 11:53:26.247  5765  5765 V BluetoothAdapterState: isTurningOn()=true
,11-09 11:53:26.247  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.247  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
,11-09 11:53:26.248  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:26.248  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:26.248  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.248  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:26.248  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:26.248  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:26.248  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.248  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:26.249  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:26.249  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:26.249  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.249  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
,11-09 11:53:26.249  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-09 11:53:26.249  5765  5777 D BluetoothAdapterProperties: ScanMode =  20
11-09 11:53:26.249  5765  5777 D BluetoothAdapterProperties: State =  11
11-09 11:53:26.251  5765  5781 D BluetoothAdapterProperties: Scan Mode:21
11-09 11:53:26.251  5765  5781 D BluetoothAdapterProperties: Discoverable Timeout:120
11-09 11:53:26.251  5765  5777 D BluetoothAdapterProperties: Setting state to 12
11-09 11:53:26.251  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-09 11:53:26.252  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-09 11:53:26.252  5765  5777 I BluetoothAdapterState: Entering OnState
11-09 11:53:26.252  5716  5726 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-09 11:53:26.252  3052  3067 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-09 11:53:26.254   926   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-09 11:53:26.254  3052  3052 D BluetoothInputDevice: Proxy object connected
11-09 11:53:26.254  3052  3052 D HidProfile: Bluetooth service connected
11-09 11:53:26.255  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-09 11:53:26.255  3754  3952 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 11:53:26.255   926   926 D BluetoothA2dp: Proxy object connected
11-09 11:53:26.255  3052  3065 D BluetoothPan: onBluetoothStateChange on: true
11-09 11:53:26.258   926   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 11:53:26.259  3052  3052 D BluetoothPan: BluetoothPAN Proxy object connected
11-09 11:53:26.259  3052  3052 D PanProfile: Bluetooth service connected
11-09 11:53:26.258  5716  5728 D BluetoothPbap: onBluetoothStateChange: up=true
11-09 11:53:26.259  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-09 11:53:26.261  3052  3065 D BluetoothPbap: onBluetoothStateChange: up=true
11-09 11:53:26.263  5765  5765 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-09 11:53:26.263  3052  3067 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 11:53:26.263  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:26.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:26.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:26.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:26.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:26.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:26.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:26.263  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:26.263  5765  5765 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-09 11:53:26.263   926   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 11:53:26.263  5716  5727 D BluetoothPan: onBluetoothStateChange on: true
11-09 11:53:26.265  3052  3935 D BluetoothMap: onBluetoothStateChange: up=true
11-09 11:53:26.265  5765  5765 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 11:53:26.265  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-09 11:53:26.267  5765  5765 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 11:53:26.267  3052  3052 D BluetoothMap: Proxy object connected
11-09 11:53:26.267  3052  3052 D MapProfile: Bluetooth service connected
11-09 11:53:26.267  3052  3052 D BluetoothMap: getConnectedDevices()
11-09 11:53:26.267   926   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 11:53:26.268  5716  5726 D BluetoothMap: onBluetoothStateChange: up=true
11-09 11:53:26.268  3052  3067 D BluetoothA2dp: onBluetoothStateChange: up=true
11-09 11:53:26.269  5765  5765 D ObexServerSockets: Succeed to create listening sockets 
11-09 11:53:26.269  5765  5765 D ObexServerSockets0: startAccept()
11-09 11:53:26.269  5765  5765 D ObexServerSockets0: prepareForNewConnect()
11-09 11:53:26.269  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:26.269  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:26.269  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:26.269  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:26.269  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:26.269  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:26.269  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:26.269  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:26.270  3052  3052 D BluetoothA2dp: Proxy object connected
11-09 11:53:26.271   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-09 11:53:26.271  5765  5765 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-09 11:53:26.272  5765  5765 D BluetoothSdpJni: SDP Create record success - handle: 0
11-09 11:53:26.272  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:26.272  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 21
11-09 11:53:26.273  5765  5803 D ObexServerSockets0: Accepting socket connection...
11-09 11:53:26.273  5765  5765 D BluetoothMapService: onReceive
,11-09 11:53:26.273  5765  5765 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-09 11:53:26.273  5765  5765 D BluetoothMapService: STATE_ON
11-09 11:53:26.274  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Bluetooth enabled, restarting BLE based peer discovery...
11-09 11:53:26.274  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-09 11:53:26.275  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-09 11:53:26.275  5602  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-09 11:53:26.275  5716  5716 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-09 11:53:26.276  5602  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-09 11:53:26.279  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-09 11:53:26.279  5716  5716 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-09 11:53:26.278  5765  5802 D ObexServerSockets0: Accepting socket connection...
11-09 11:53:26.280  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-09 11:53:26.281  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 11:53:26.281  5765  5805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 11:53:26.282  5765  5805 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-09 11:53:26.282  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.282  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 11:53:26.282  5765  5805 D BluetoothSdpJni: SDP Create record success - handle: 1
11-09 11:53:26.282  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:26.282  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-09 11:53:26.283  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 11:53:26.283  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.283  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.283  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.283  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.284  5602  5602 D BluetoothAdapter: STATE_ON
11-09 11:53:26.287  5765  5792 D BtGatt.GattService: registerClient() - UUID=730bf6ac-85f5-4002-b6ff-921f8c1e043e
11-09 11:53:26.287  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-09 11:53:26.288  5765  5781 D BtGatt.GattService: onClientRegistered() - UUID=730bf6ac-85f5-4002-b6ff-921f8c1e043e, clientIf=5
,11-09 11:53:26.288  5602  5649 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-09 11:53:26.289  5716  5716 D BluetoothA2dp: Proxy object connected
11-09 11:53:26.290  5765  5783 D BtGatt.AdvertiseManager: message : 0
,11-09 11:53:26.293  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-09 11:53:26.293  5716  5716 D DockEventReceiver: finishStartingService: stopping service
11-09 11:53:26.294  5765  5783 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 11:53:26.297  5765  5781 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 11:53:26.299  5765  5781 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-09 11:53:26.300  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.300  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.300  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:26.300  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.300  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.300  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.300  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.300  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.300  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 11:53:26.301  5716  5716 D BluetoothPbap: Proxy object connected
,11-09 11:53:26.301  5716  5716 D PbapServerProfile: Bluetooth service connected
11-09 11:53:26.302  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 11:53:26.302  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.302  5765  5765 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-09 11:53:26.302  5765  5765 D ObexServerSockets0: prepareForNewConnect()
11-09 11:53:26.303  3052  3052 D BluetoothPbap: Proxy object connected
11-09 11:53:26.303  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.303  3052  3052 D PbapServerProfile: Bluetooth service connected
11-09 11:53:26.303  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 11:53:26.303  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.303  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.306  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:26.306  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:26.306  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:26.306  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:26.306  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:26.306  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:26.306  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:26.306  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 11:53:26.308  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:26.308  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-09 11:53:26.309  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:26.310  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:26.310  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 12
11-09 11:53:26.311  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: Bluetooth enabled, restarting BLE based peer discovery...
11-09 11:53:26.311  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-09 11:53:26.312  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 11:53:26.312  5602  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-09 11:53:26.314  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.314  5765  5809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 11:53:26.314  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:26.314  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-09 11:53:26.314  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 11:53:26.314  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.314  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.315  5765  5783 D BtGatt.AdvertiseManager: message : 1
11-09 11:53:26.315  5765  5783 D BtGatt.AdvertiseManager: stop advertise for client 5
11-09 11:53:26.321  5765  5781 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 11:53:26.321  5765  5781 D BtGatt.GattService: Client app is not null!
11-09 11:53:26.321  5765  5776 D BtGatt.GattService: unregisterClient() - clientIf=5
11-09 11:53:26.322  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 11:53:26.322  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.322  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
11-09 11:53:26.322  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.322  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.322  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.322  5602  ,5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.323  5602  5602 D BluetoothAdapter: STATE_ON
11-09 11:53:26.325  5765  5776 D BtGatt.GattService: registerClient() - UUID=51052795-8daa-4f5f-9589-530c18a12a05
11-09 11:53:26.326  5765  5781 D BtGatt.GattService: onClientRegistered() - UUID=51052795-8daa-4f5f-9589-530c18a12a05, clientIf=5
11-09 11:53:26.326  5602  5649 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-09 11:53:26.327  5765  5783 D BtGatt.AdvertiseManager: message : 0
,11-09 11:53:26.329  5765  5813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 11:53:26.329  5765  5783 D BtGatt.AdvertiseManager: starting multi advertising
11-09 11:53:26.330  5765  5813 I BtOppRfcommListener: Accept thread started.
11-09 11:53:26.332  5765  5781 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 11:53:26.335  5765  5781 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-09 11:53:26.336  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:26.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.336  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Already running
11-09 11:53:26.336  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.336  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-09 11:53:26.337  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 11:53:26.338  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.339  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.339  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.339  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.340  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:26.341  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.341  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.341  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 11:53:26.341  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.341  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.341  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.341  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 11:53:26.341  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-09 11:53:26.341  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.341  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.341  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-09 11:53:26.341  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.343  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.343  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 11:53:26.343  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.343  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.343  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.343  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.343  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 11:53:26.344  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.344  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.344  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.344  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-09 11:53:26.356   926   926 D BluetoothHeadset: Proxy object connected
,11-09 11:53:26.357  3754  3778 D BluetoothHeadset: Proxy object connected
11-09 11:53:26.357   926   926 D BluetoothHeadset: Proxy object connected
11-09 11:53:26.357  3052  3935 D BluetoothHeadset: Proxy object connected
11-09 11:53:26.357  3052  3052 D HeadsetProfile: Bluetooth service connected
11-09 11:53:26.357   926   926 D BluetoothHeadset: Proxy object connected
11-09 11:53:26.359   926   944 D BluetoothHeadset: Proxy object connected
,11-09 11:53:26.363  3052  3065 D BluetoothHeadset: Proxy object connected
11-09 11:53:26.363  3052  3052 D HeadsetProfile: Bluetooth service connected
,11-09 11:53:26.363   926   944 D BluetoothHeadset: Proxy object connected
,11-09 11:53:26.368   926   944 D BluetoothHeadset: Proxy object connected
,11-09 11:53:26.383  5716  5727 D BluetoothHeadset: Proxy object connected
,11-09 11:53:26.384  5716  5716 D HeadsetProfile: Bluetooth service connected
,11-09 11:53:26.566  5703  5703 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 11:53:26.567  5703  5703 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-09 11:53:26.568  5703  5703 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-09 11:53:26.570  5703  5703 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 11:53:26.615   926  2950 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-09 11:53:26.616   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-09 11:53:26.616   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 11:53:26.626   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-09 11:53:26.663   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-09 11:53:26.668  5703  5703 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-09 11:53:26.705  5602  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:26.707  5602  5648 D io.jxcore.node.ConnectivityMonitor: stop
11-09 11:53:26.707  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-09 11:53:26.710  5602  5648 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-09 11:53:26.711  5602  5648 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-09 11:53:26.715  5602  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:26.719  5765  5777 D BluetoothAdapterState: Current state: ON, message: 23
,11-09 11:53:26.719  5765  5777 D BluetoothAdapterProperties: Setting state to 13
11-09 11:53:26.719  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-09 11:53:26.722  5765  5777 D BluetoothAdapterProperties: onBluetoothDisable()
,11-09 11:53:26.724  5765  5777 I BluetoothAdapterState: Entering PendingCommandState
,11-09 11:53:26.725  5765  5765 D BluetoothMapService: onReceive
11-09 11:53:26.725  5765  5765 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-09 11:53:26.726  5765  5765 D BluetoothMapService: STATE_TURNING_OFF
11-09 11:53:26.726  5765  5765 D BluetoothMapService: MAP Service closeService in
11-09 11:53:26.726  5765  5765 D BluetoothMapMasInstance0: MAP Service shutdown
11-09 11:53:26.726  5765  5765 D ObexServerSockets0: shutdown(block = true)
11-09 11:53:26.728  5765  5765 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-09 11:53:26.728  5765  5765 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-09 11:53:26.728  5765  5781 D BluetoothAdapterProperties: Scan Mode:20
11-09 11:53:26.728  5765  5802 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-09 11:53:26.729  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-09 11:53:26.730  5765  5803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-09 11:53:26.731  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:26.731  5765  5790 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-09 11:53:26.732  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:26.732  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:26.732  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:26.732  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:26.732  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 11:53:26.732  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:26.732  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:26.732  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:26.733  5765  5765 I BtOppRfcommListener: stopping Accept Thread
11-09 11:53:26.733  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:26.733  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-09 11:53:26.734  5765  5813 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-09 11:53:26.734  5765  5813 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-09 11:53:26.739  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:26.739  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:26.739  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:26.739  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:26.739  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:26.739  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 11:53:26.739  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:26.739  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:26.739  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:26.740  5765  5765 D HeadsetService: Received stop request...Stopping profile...
11-09 11:53:26.740  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:26.741  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-09 11:53:26.741  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 13
,11-09 11:53:26.742   926   926 D BluetoothHeadset: Proxy object disconnected
,11-09 11:53:26.742  3754  3952 D BluetoothHeadset: Proxy object disconnected
11-09 11:53:26.742   926   926 D BluetoothHeadset: Proxy object disconnected
11-09 11:53:26.743  5716  5728 D BluetoothHeadset: Proxy object disconnected
11-09 11:53:26.743  3052  3935 D BluetoothHeadset: Proxy object disconnected
11-09 11:53:26.743   926   926 D BluetoothHeadset: Proxy object disconnected
11-09 11:53:26.744  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:26.745  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:26.745  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-09 11:53:26.746  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-09 11:53:26.746  5602  5602 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Bluetooth disabled, pausing BLE based peer discovery...
11-09 11:53:26.746  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.746  5765  5765 D A2dpService: Received stop request...Stopping profile...
11-09 11:53:26.746  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.746  5765  5797 D A2dpStateMachine: Exit Disconnected: -1
11-09 11:53:26.747  5602  5602 D BluetoothAdapter: STATE_OFF
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: BT Adapter is not turned ON
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: java.lang.IllegalStateException: BT Adapter is not turned ON
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.bluetooth.le.BluetoothLeUtils.checkAdapterStateOn(BluetoothLeUtils.java:136)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.bluetooth.le.BluetoothLeScanner.stopScan(BluetoothLeScanner.java:169)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner.stop(BleScanner.java:150)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stopScanner(BlePeerDiscoverer.java:436)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stopScannerAndAdvertiser(BlePeerDiscoverer.java:503)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.stopBlePeerDiscoverer(DiscoveryManager.java:1217)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.onBluetoothAdapterScanModeChanged(DiscoveryManager.java:742)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver.onReceive(BluetoothManager.java:552)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:53:26.747  5602  5602 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-09 11:53:26.747  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.747   926   926 D BluetoothA2dp: Proxy object disconnected
11-09 11:53:26.747  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.747  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-09 11:53:26.747  5716  5716 D HeadsetProfile: Bluetooth service disconnected
11-09 11:53:26.748  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.748  5765  5783 D BtGatt.AdvertiseManager: message : 1
11-09 11:53:26.748  5765  5783 D BtGatt.AdvertiseManager: stop advertise for client 5
11-09 11:53:26.750  5716  5716 D DockEventReceiver: finishStartingService: stopping service
,11-09 11:53:26.751  5716  5716 D BluetoothA2dp: Proxy object disconnected
,11-09 11:53:26.752  5765  5781 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 11:53:26.752  5765  5781 D BtGatt.GattService: Client app is not null!
11-09 11:53:26.753  5765  5804 D BtGatt.GattService: unregisterClient() - clientIf=5
11-09 11:53:26.754  5765  5765 D HidService: Received stop request...Stopping profile...
11-09 11:53:26.754  5765  5765 D HidService: Stopping Bluetooth HidService
,11-09 11:53:26.754  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 11:53:26.754  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
,11-09 11:53:26.754  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-09 11:53:26.754  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.754  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.754  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.754  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-09 11:53:26.754  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-09 11:53:26.754  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.754  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.754  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-09 11:53:26.755  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.755  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:26.755  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:26.755  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.755  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:26.755  3052  3052 D HeadsetProfile: Bluetooth service disconnected
11-09 11:53:26.755  5765  5765 D HealthService: Received stop request...Stopping profile...
11-09 11:53:26.756  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.756  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
11-09 11:53:26.756  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.756  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.756  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.756  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:26.756  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.756  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-09 11:53:26.756  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.758  5765  5765 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-09 11:53:26.758  5765  5765 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-09 11:53:26.758  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 11:53:26.758  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.758  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-09 11:53:26.758  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 11:53:26.758  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.758  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.758  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
11-09 11:53:26.758  5765  5765 D PanService: Received stop request...Stopping profile...
11-09 11:53:26.759  5716  5716 D BluetoothInputDevice: Proxy object disconnected
11-09 11:53:26.759  5716  5716 D HidProfile: Bluetooth service disconnected
11-09 11:53:26.759  5716  5716 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-09 11:53:26.759  5716  5716 D PanProfile: Bluetooth service disconnected
11-09 11:53:26.760  5765  5765 D BluetoothMapService: Received stop request...Stopping profile...
11-09 11:53:26.760  5765  5765 D BluetoothMapService: stop()
11-09 11:53:26.760  3052  3052 D BluetoothA2dp: Proxy object disconnected
,11-09 11:53:26.760  3052  3052 D BluetoothInputDevice: Proxy object disconnected
11-09 11:53:26.760  3052  3052 D HidProfile: Bluetooth service disconnected
11-09 11:53:26.760  3052  3052 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-09 11:53:26.760  3052  3052 D PanProfile: Bluetooth service disconnected
11-09 11:53:26.760  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-09 11:53:26.760  5765  5765 D BluetoothMapAppObserver: deinitObservers()
11-09 11:53:26.760  5765  5781 E bt_btif : btif_hf_upstreams_evt: Invalid index 1283
11-09 11:53:26.760  5765  5765 D BluetoothMapAppObserver: removeReceiver()
11-09 11:53:26.762  3052  3052 D BluetoothMap: Proxy object disconnected
11-09 11:53:26.762  3052  3052 D MapProfile: Bluetooth service disconnected
11-09 11:53:26.762  5765  5765 D SapService: Received stop request...Stopping profile...
11-09 11:53:26.762  5765  5765 V SapService: stop()
11-09 11:53:26.764  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:26.764  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:26.764  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.764  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:26.764  5716  5716 D BluetoothMap: Proxy object disconnected
11-09 11:53:26.764  5716  5716 D MapProfile: Bluetooth service disconnected
11-09 11:53:26.765  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 11:53:26.765  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-09 11:53:26.765  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 11:53:26.766  5765  5788 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-09 11:53:26.766  5765  5788 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-09 11:53:26.766  5765  5788 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-09 11:53:26.766  5765  5788 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-09 11:53:26.767  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:26.768  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:26.768  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.768  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:26.768  5765  5765 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-09 11:53:26.768  5765  5765 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-09 11:53:26.768  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-09 11:53:26.768  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:26.768  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:26.768  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.768  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:26.769  5765  5765 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-09 11:53:26.769  5765  5781 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-09 11:53:26.769  5765  5765 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-09 11:53:26.769  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:26.769  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:26.769  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.769  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:26.769  5765  5765 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-09 11:53:26.770  5765  5765 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-09 11:53:26.771  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-09 11:53:26.771  5765  5765 D BluetoothMapService: MAP Service closeService in
11-09 11:53:26.771  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:26.771  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:26.771  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.771  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:26.772  5765  5765 D BluetoothMapService: cleanup()
11-09 11:53:26.772  5765  5765 D BluetoothMapService: MAP Service closeService in
11-09 11:53:26.772  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-09 11:53:26.772  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:26.772  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:26.772  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:26.772  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-09 11:53:26.772  5765  5777 D BluetoothAdapterProperties: Setting state to 15
11-09 11:53:26.772  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-09 11:53:26.772  5765  5777 I BluetoothAdapterState: Entering BleOnState
11-09 11:53:26.773  3052  3052 D BluetoothPbap: Proxy object disconnected
11-09 11:53:26.773  3052  3052 D PbapServerProfile: Bluetooth service disconnected
11-09 11:53:26.773  5716  5716 D BluetoothPbap: Proxy object disconnected
11-09 11:53:26.773  5716  5716 D PbapServerProfile: Bluetooth service disconnected
,11-09 11:53:26.774  5716  5728 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-09 11:53:26.774  3052  3067 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-09 11:53:26.775   926   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-09 11:53:26.775  3754  3778 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 11:53:26.775  3052  3935 D BluetoothPan: onBluetoothStateChange on: false
11-09 11:53:26.775   926   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 11:53:26.776  5716  5727 D BluetoothPbap: onBluetoothStateChange: up=false
11-09 11:53:26.776  5716  5726 D BluetoothA2dp: onBluetoothStateChange: up=false
11-09 11:53:26.776  3052  3065 D BluetoothPbap: onBluetoothStateChange: up=false
11-09 11:53:26.777  5716  5728 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-09 11:53:26.778  3052  3067 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 11:53:26.778   926   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 11:53:26.778  5716  5727 D BluetoothPan: onBluetoothStateChange on: false
11-09 11:53:26.780  3052  3935 D BluetoothMap: onBluetoothStateChange: up=false
11-09 11:53:26.781   926   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 11:53:26.781  5716  5726 D BluetoothMap: onBluetoothStateChange: up=false
11-09 11:53:26.781  3052  3065 D BluetoothA2dp: onBluetoothStateChange: up=false
11-09 11:53:26.782  5765  5777 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-09 11:53:26.782  5765  5777 D BluetoothAdapterProperties: Setting state to 16
,11-09 11:53:26.782  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-09 11:53:26.783  5765  5777 D BluetoothAdapterProperties: onBleDisable
11-09 11:53:26.783  5765  5777 I BluetoothAdapterState: Entering PendingCommandState
11-09 11:53:26.783  5765  5778 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-09 11:53:26.783  5765  5781 D BluetoothAdapterProperties: Scan Mode:20
11-09 11:53:26.784  5765  5788 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-09 11:53:26.784  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 11:53:26.786  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:26.788  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:26.788  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 10
11-09 11:53:26.788  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.790  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.790  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.790  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.791  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-09 11:53:26.791  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:26.792  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:26.792  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-09 11:53:26.792  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.793  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.793  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:26.794  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-09 11:53:26.795  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-09 11:53:26.799  5716  5716 D DockEventReceiver: finishStartingService: stopping service
,11-09 11:53:26.984  5765  5781 I bt_hci  : shut_down
,11-09 11:53:26.984  5765  5785 D bt_hwcfg: hw_epilog_process
,11-09 11:53:26.985  5765  5785 I bt_vendor: low_power_mode_cb
,11-09 11:53:26.989  5765  5785 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-09 11:53:26.989  5765  5785 I bt_vendor: epilog_cb
11-09 11:53:26.989  5765  5785 I bt_hci  : epilog_finished_callback
11-09 11:53:26.990  5765  5781 I bt_hci_h4: hal_close
,11-09 11:53:26.991  5765  5781 I bt_userial_vendor: device fd = 54 close
,11-09 11:53:27.094  5703  5703 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-09 11:53:27.116  5765  5778 D bt_stack_manager: event_shut_down_stack finished.
,11-09 11:53:27.117  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-09 11:53:27.119  5765  5777 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-09 11:53:27.120  5765  5765 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-09 11:53:27.121  5765  5765 D BtGatt.GattService: Received stop request...Stopping profile...
,11-09 11:53:27.121  5765  5765 D BtGatt.GattService: stop()
11-09 11:53:27.121  5765  5765 D BtGatt.AdvertiseManager: advertise clients cleared
,11-09 11:53:27.124  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:27.125  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:27.125  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
,11-09 11:53:27.125  5765  5765 V BluetoothAdapterState: isBleTurningOff()=true
11-09 11:53:27.125  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-09 11:53:27.126  5765  5777 D BluetoothAdapterProperties: Setting state to 10
,11-09 11:53:27.126  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-09 11:53:27.126  5765  5777 I BluetoothAdapterState: Entering OffState
,11-09 11:53:27.128   926   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-09 11:53:27.136  5703  5703 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
11-09 11:53:27.136  5703  5703 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-09 11:53:27.141  5765  5765 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-09 11:53:27.141  5765  5765 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-09 11:53:27.141  5765  5765 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-09 11:53:27.144  5765  5778 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-09 11:53:27.145   926  2950 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-09 11:53:27.145   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 11:53:27.145   926  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-09 11:53:27.151  5765  5765 I art     : System.exit called, status: 0
11-09 11:53:27.152  5765  5765 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-09 11:53:27.160   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 11:53:27.171   507   919 D CommandListener: Setting iface cfg
,11-09 11:53:27.175   926  2950 D WifiStateMachine: Start Dhcp Watchdog 2
,11-09 11:53:27.184   926  5822 D DhcpClient: Receive thread started
,11-09 11:53:27.189   926   936 I ActivityManager: Process com.android.bluetooth (pid 5765) has died
,11-09 11:53:27.192   926  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-09 11:53:27.192   926  2954 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
11-09 11:53:27.192   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-09 11:53:27.218  5602  5665 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-09 11:53:27.218  5602  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:27.218  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:27.218  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:27.218  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:27.218  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 11:53:27.218  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:27.218  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:27.218  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:27.218  5602  5665 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:27.218  5602  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:27.220  5602  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:27.230   926   944 I ActivityManager: Start proc 5823:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-09 11:53:27.258  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-09 11:53:27.272   926  2950 E native  : do suspend false
,11-09 11:53:27.280   926  5821 D DhcpClient: Broadcasting DHCPDISCOVER
,11-09 11:53:27.291  5823  5823 D AdapterServiceConfig: Adding HeadsetService
,11-09 11:53:27.291  5823  5823 D AdapterServiceConfig: Adding A2dpService
11-09 11:53:27.291  5823  5823 D AdapterServiceConfig: Adding HidService
11-09 11:53:27.291  5823  5823 D AdapterServiceConfig: Adding HealthService
11-09 11:53:27.291  5823  5823 D AdapterServiceConfig: Adding PanService
,11-09 11:53:27.291  5823  5823 D AdapterServiceConfig: Adding GattService
11-09 11:53:27.292  5823  5823 D AdapterServiceConfig: Adding BluetoothMapService
11-09 11:53:27.292  5823  5823 D AdapterServiceConfig: Adding SapService
11-09 11:53:27.293   926  5822 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172732, domain null
11-09 11:53:27.294   926  5821 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172732 seconds
,11-09 11:53:27.295   926  5821 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-09 11:53:27.302   926   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@40b8a03:true
,11-09 11:53:27.302  5823  5823 D BluetoothAdapterState: make() - Creating AdapterState
,11-09 11:53:27.304  5823  5823 I bt_bluedroid: init
,11-09 11:53:27.304  5823  5835 I BluetoothAdapterState: Entering OffState
,11-09 11:53:27.306  5823  5836 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-09 11:53:27.306  5823  5836 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-09 11:53:27.306  5823  5836 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-09 11:53:27.306  5823  5836 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-09 11:53:27.307  5823  5823 I bt_bluedroid: get_profile_interface socket
11-09 11:53:27.307   926  5822 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-09 11:53:27.308   926  5821 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-09 11:53:27.308  5823  5823 I bt_bluedroid: get_profile_interface sdp
,11-09 11:53:27.308  5823  5839 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-09 11:53:27.309   507   919 D CommandListener: Setting iface cfg
11-09 11:53:27.309  5823  5839 D BluetoothAdapterProperties: Name is: Nexus 6P
11-09 11:53:27.311   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
11-09 11:53:27.312  5823  5834 I bt_bluedroid: config_hci_snoop_log
,11-09 11:53:27.313   926   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-09 11:53:27.314   926  5821 D DhcpClient: Scheduling renewal in 86399s
,11-09 11:53:27.317  5823  5835 D BluetoothAdapterState: Current state: OFF, message: 0
,11-09 11:53:27.317  5823  5835 D BluetoothAdapterProperties: Setting state to 14
11-09 11:53:27.317  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-09 11:53:27.319  5823  5835 D BluetoothBondStateMachine: make
,11-09 11:53:27.320   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-09 11:53:27.321  5823  5840 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-09 11:53:27.321   926  2950 D WifiConfigStore: No blacklist allowed without epno enabled
11-09 11:53:27.321   926  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-09 11:53:27.324   926  2954 D ConnectivityService: Adding iface wlan0 to network 101
,11-09 11:53:27.324   926  2950 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-09 11:53:27.327  5823  5835 I BluetoothAdapterState: Entering PendingCommandState
,11-09 11:53:27.327  5823  5823 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-09 11:53:27.329  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
11-09 11:53:27.330  5823  5823 D BtGatt.DebugUtils: handleDebugAction() action=null
11-09 11:53:27.331  5823  5823 D BtGatt.GattService: Received start request. Starting profile...
11-09 11:53:27.331  5823  5823 D BtGatt.GattService: start()
11-09 11:53:27.331  5823  5823 I bt_bluedroid: get_profile_interface gatt
,11-09 11:53:27.332  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:27.332  5823  5823 D BtGatt.AdvertiseManager: advertise manager created
,11-09 11:53:27.336  5823  5823 V BluetoothAdapterState: isTurningOff()=false
,11-09 11:53:27.336  5823  5823 V BluetoothAdapterState: isTurningOn()=false
11-09 11:53:27.336  5823  5823 V BluetoothAdapterState: isBleTurningOn()=true
11-09 11:53:27.336  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:27.337  5823  5835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-09 11:53:27.338  5823  5835 I bt_bluedroid: bt_bluedroid
11-09 11:53:27.338  5823  5836 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-09 11:53:27.338  5823  5836 I bt_hci  : start_up
11-09 11:53:27.343  5823  5836 I bt_vendor: alloc value 0xf3dbb871
11-09 11:53:27.343  5823  5836 I bt_vendor: init
11-09 11:53:27.343  5823  5836 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-09 11:53:27.343  5823  5836 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-09 11:53:27.347   926  2954 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-09 11:53:27.347   926  2954 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-09 11:53:27.348   926  2954 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-09 11:53:27.349   926  2954 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-09 11:53:27.352   926  2954 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-09 11:53:27.357   926  2954 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-09 11:53:27.360   926  2954 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-09 11:53:27.360   926  2954 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-09 11:53:27.360   926  2954 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-09 11:53:27.360   926  2950 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-09 11:53:27.360   926  2954 D ConnectivityService:    accepting network in place of null
11-09 11:53:27.360   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-09 11:53:27.361   926  2954 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-09 11:53:27.374   926  5820 D NetlinkSocketObserver: NeighborEvent{elapsedMs=108080, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-09 11:53:27.381   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 11:53:27.398   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 11:53:27.402   926  2954 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-09 11:53:27.402   926  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-09 11:53:27.402  3708  3826 W QCNEJ   : |CORE| network available: 101
,11-09 11:53:27.403   926  2954 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-09 11:53:27.405   926   944 D Tethering: MasterInitialState.processMessage what=3
,11-09 11:53:27.409  3708  3826 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-09 11:53:27.413  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:27.413  3908  3908 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-09 11:53:27.413  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:27.413  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:27.413  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:27.413  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:27.413  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 11:53:27.413  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:27.413  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:53:27.413  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 11:53:27.414  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:27.414  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:27.414  3708  3826 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-09 11:53:27.414  3708  3826 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-09 11:53:27.417  3922  3922 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-09 11:53:27.418  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:27.418  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:27.418  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:27.418  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:27.418  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:27.418  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 11:53:27.418  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:27.418  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:53:27.418  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 11:53:27.419  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 11:53:27.419  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 11:53:27.423  3922  3922 D SystemUpdateService: onCreate
,11-09 11:53:27.426  3922  3922 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-09 11:53:27.437  3922  3922 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-09 11:53:27.442  3922  4269 I iu.UploadsManager: num queued entries: 0
11-09 11:53:27.443  3922  4269 I iu.UploadsManager: num updated entries: 0
,11-09 11:53:27.443  3922  4269 I iu.SyncManager: NEXT; no task
,11-09 11:53:27.446  3922  5852 I SystemUpdateService: active receiver: enabled
,11-09 11:53:27.447  3922  3922 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-09 11:53:27.448  3922  3922 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-09 11:53:27.450  5379  5379 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-09 11:53:27.447  5856  5856 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-09 11:53:27.450  5823  5836 D bt_hci  : start_up starting async portion
11-09 11:53:27.451  5823  5845 I bt_hci  : event_finish_startup
11-09 11:53:27.451  5823  5845 I bt_hci_h4: hal_open
11-09 11:53:27.451  5823  5845 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-09 11:53:27.451  5823  5845 I bt_userial_vendor: device fd = 54 open
,11-09 11:53:27.454   926  5818 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-09 11:53:27.454  5379  5379 D SprintDMHelper: simOperator: 
11-09 11:53:27.455  5379  5379 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-09 11:53:27.464  5823  5845 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-09 11:53:27.466  5823  5845 D bt_hwcfg: Chipset BCM4358A3
,11-09 11:53:27.466  5823  5845 D bt_hwcfg: Target name = [BCM4358A3]
11-09 11:53:27.466  5823  5845 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-09 11:53:27.473  3922  5852 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-09 11:53:27.480  3922  5852 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-09 11:53:27.480  3922  5852 I SystemUpdateService: now status is 0 (complete)
,11-09 11:53:27.480  3922  5852 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-09 11:53:27.480  3922  5852 I SystemUpdateService: file has been verified
11-09 11:53:27.480  3922  5852 I SystemUpdateService: OTA package size = 21989297
,11-09 11:53:27.486  3922  5852 I SystemUpdateService: showing system update notification
,11-09 11:53:27.494   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-09 11:53:27.495  3922  3922 D SystemUpdateService: onDestroy
,11-09 11:53:27.513   926  5818 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Nov 2016 10:53:27 GMT], X-Android-Received-Millis=[1478688807512], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478688807488]}
,11-09 11:53:27.513   926  2954 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-09 11:53:27.513   926  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-09 11:53:27.513   926  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-09 11:53:27.514   926  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-09 11:53:27.728  5823  5835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-09 11:53:27.789  5823  5845 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-09 11:53:27.789  5823  5845 D bt_hwcfg: Settlement delay -- 100 ms
,11-09 11:53:27.789  5823  5845 I bt_hwcfg: Setting fw settlement delay to 100 
,11-09 11:53:27.913  5823  5845 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-09 11:53:27.914  5823  5845 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-09 11:53:27.915  5823  5845 I bt_hwcfg: vendor lib fwcfg completed
11-09 11:53:27.915  5823  5845 I bt_vendor: firmware callback
11-09 11:53:27.916  5823  5845 I bt_hci  : firmware_config_callback
,11-09 11:53:27.925  5823  5862 I bt_btu  : btu_task pending for preload complete event
,11-09 11:53:27.925  5823  5862 I bt_btu_task: Bluetooth chip preload is complete
,11-09 11:53:27.925  5823  5862 I bt_btu  : btu_task received preload complete event
,11-09 11:53:27.933  5823  5862 I         : BTE_InitTraceLevels -- TRC_HCI
,11-09 11:53:27.934  5823  5862 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-09 11:53:27.934  5823  5862 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-09 11:53:27.934  5823  5862 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-09 11:53:27.934  5823  5862 I         : BTE_InitTraceLevels -- TRC_AVRC
11-09 11:53:27.934  5823  5862 I         : BTE_InitTraceLevels -- TRC_A2D
11-09 11:53:27.934  5823  5862 I         : BTE_InitTraceLevels -- TRC_BNEP
11-09 11:53:27.934  5823  5862 I         : BTE_InitTraceLevels -- TRC_BTM
,11-09 11:53:27.934  5823  5862 I         : BTE_InitTraceLevels -- TRC_GAP
11-09 11:53:27.935  5823  5862 I         : BTE_InitTraceLevels -- TRC_PAN
11-09 11:53:27.935  5823  5862 I         : BTE_InitTraceLevels -- TRC_SDP
,11-09 11:53:27.935  5823  5862 I         : BTE_InitTraceLevels -- TRC_GATT
11-09 11:53:27.935  5823  5862 I         : BTE_InitTraceLevels -- TRC_SMP
11-09 11:53:27.935  5823  5862 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-09 11:53:27.935  5823  5862 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-09 11:53:28.018  5823  5862 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d39549
,11-09 11:53:28.019  5823  5862 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d39549 
,11-09 11:53:28.029  5823  5839 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-09 11:53:28.031  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-09 11:53:28.031  5823  5839 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-09 11:53:28.034  5823  5839 D BluetoothAdapterProperties: Name is: Nexus 6P
11-09 11:53:28.036  5823  5839 D BluetoothAdapterProperties: Scan Mode:20
11-09 11:53:28.037  5823  5839 D BluetoothAdapterProperties: Discoverable Timeout:120
11-09 11:53:28.037  5823  5839 D bt_hci  : do_postload posting postload work item
11-09 11:53:28.039  5823  5845 I bt_hci  : event_postload
11-09 11:53:28.039  5823  5845 I bt_vendor: sco_config_cb
11-09 11:53:28.039  5823  5845 I bt_hci  : sco_config_callback postload finished.
,11-09 11:53:28.044  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:28.044  5823  5839 D bt_bte_conf: Device ID record 1 : primary
11-09 11:53:28.045  5823  5839 D bt_bte_conf:   vendorId            = 000f
11-09 11:53:28.045  5823  5839 D bt_bte_conf:   vendorIdSource      = 0001
11-09 11:53:28.045  5823  5839 D bt_bte_conf:   product             = 1200
11-09 11:53:28.045  5823  5839 D bt_bte_conf:   version             = 1436
11-09 11:53:28.045  5823  5839 D bt_bte_conf:   clientExecutableURL = 
11-09 11:53:28.045  5823  5839 D bt_bte_conf:   serviceDescription  = 
11-09 11:53:28.045  5823  5839 D bt_bte_conf:   documentationURL    = 
11-09 11:53:28.045  5823  5839 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-09 11:53:28.046  5823  5836 D bt_stack_manager: event_start_up_stack finished
,11-09 11:53:28.048  5823  5845 I bt_vendor: low_power_mode_cb
,11-09 11:53:28.050  5823  5835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-09 11:53:28.050  5823  5835 D BluetoothAdapterProperties: Setting state to 15
11-09 11:53:28.051  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:28.051  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-09 11:53:28.051  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-09 11:53:28.052  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:28.054  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.054  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-09 11:53:28.054  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.055  5823  5835 I BluetoothAdapterState: Entering BleOnState
11-09 11:53:28.057  5823  5835 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-09 11:53:28.057  5823  5835 D BluetoothAdapterProperties: Setting state to 11
,11-09 11:53:28.057  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-09 11:53:28.065  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:28.067  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
11-09 11:53:28.068  5823  5823 D HeadsetService: Received start request. Starting profile...
,11-09 11:53:28.070  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:28.070  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 11
11-09 11:53:28.072  5823  5823 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-09 11:53:28.072  5823  5823 D HeadsetStateMachine: make
,11-09 11:53:28.078  5823  5835 I BluetoothAdapterState: Entering PendingCommandState
,11-09 11:53:28.083  5823  5823 D HeadsetStateMachine: max_hf_connections = 1
,11-09 11:53:28.083  5823  5823 I bt_bluedroid: get_profile_interface handsfree
11-09 11:53:28.083  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-09 11:53:28.083  5823  5839 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-09 11:53:28.087  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:28.088  5823  5823 D A2dpService: Received start request. Starting profile...
,11-09 11:53:28.088  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-09 11:53:28.088  5823  5823 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-09 11:53:28.089  5823  5823 I bt_bluedroid: get_profile_interface avrcp
,11-09 11:53:28.095  5823  5823 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-09 11:53:28.095  5823  5823 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-09 11:53:28.095  5823  5823 D A2dpStateMachine: make
11-09 11:53:28.096  5823  5823 I bt_bluedroid: get_profile_interface a2dp
,11-09 11:53:28.097  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-09 11:53:28.098  5823  5871 D A2dpStateMachine: Enter Disconnected: -2
,11-09 11:53:28.098  5823  5823 I BluetoothHidServiceJni: classInitNative: succeeds
,11-09 11:53:28.099  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:28.100  5823  5823 D HidService: Received start request. Starting profile...
,11-09 11:53:28.100  5823  5823 I bt_bluedroid: get_profile_interface hidhost
11-09 11:53:28.100  5823  5823 D HidService: setHidService(): set to: null
11-09 11:53:28.101  5823  5839 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d1a56d
,11-09 11:53:28.101  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-09 11:53:28.101  5823  5823 I BluetoothHealthServiceJni: classInitNative: succeeds
11-09 11:53:28.102  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
11-09 11:53:28.102  5823  5823 D HealthService: Received start request. Starting profile...
,11-09 11:53:28.103  5823  5823 I bt_bluedroid: get_profile_interface health
11-09 11:53:28.104  5823  5823 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-09 11:53:28.105  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
11-09 11:53:28.105  5823  5823 D PanService: Received start request. Starting profile...
11-09 11:53:28.106  5823  5823 D BluetoothPanServiceJni: initializeNative(L110): pan
11-09 11:53:28.106  5823  5823 I bt_bluedroid: get_profile_interface pan
11-09 11:53:28.106  5823  5839 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-09 11:53:28.108  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:28.109  5823  5823 D BluetoothMapService: Received start request. Starting profile...
,11-09 11:53:28.109  5823  5823 D BluetoothMapService: start()
11-09 11:53:28.111  5823  5823 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-09 11:53:28.112  5823  5823 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-09 11:53:28.112  5823  5823 D BluetoothMapAppObserver: createReceiver()
,11-09 11:53:28.113  5823  5823 D BluetoothMapAppObserver: initObservers()
11-09 11:53:28.113  5823  5823 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-09 11:53:28.119  5823  5823 V SapService: SapBinder()
,11-09 11:53:28.119  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
11-09 11:53:28.120  5823  5823 D SapService: Received start request. Starting profile...
11-09 11:53:28.120  5823  5823 V SapService: start()
,11-09 11:53:28.123  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:28.123  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:28.123  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:28.123  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:28.123  5823  5869 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-09 11:53:28.123  5823  5823 V BluetoothAdapterState: isTurningOff()=false
,11-09 11:53:28.123  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:28.123  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:28.124  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:28.125  5823  5823 V BluetoothAdapterState: isTurningOff()=false
,11-09 11:53:28.125  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-09 11:53:28.125  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-09 11:53:28.125  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-09 11:53:28.125  5823  5835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-09 11:53:28.125  5823  5835 D BluetoothAdapterProperties: ScanMode =  20
11-09 11:53:28.125  5823  5835 D BluetoothAdapterProperties: State =  11
11-09 11:53:28.126  5823  5839 D BluetoothAdapterProperties: Scan Mode:21
11-09 11:53:28.127  5823  5835 D BluetoothAdapterProperties: Setting state to 12
11-09 11:53:28.127  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-09 11:53:28.127  5823  5839 D BluetoothAdapterProperties: Discoverable Timeout:120
11-09 11:53:28.127  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-09 11:53:28.127  5716  5726 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-09 11:53:28.129  3052  3067 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-09 11:53:28.131  5823  5835 I BluetoothAdapterState: Entering OnState
11-09 11:53:28.131  3052  3052 D BluetoothInputDevice: Proxy object connected
11-09 11:53:28.131  3052  3052 D HidProfile: Bluetooth service connected
11-09 11:53:28.131   926   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-09 11:53:28.132  3754  3779 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 11:53:28.132  3052  3935 D BluetoothPan: onBluetoothStateChange on: true
11-09 11:53:28.133  5716  5716 D BluetoothInputDevice: Proxy object connected
11-09 11:53:28.133  5716  5716 D HidProfile: Bluetooth service connected
,11-09 11:53:28.133   926   926 D BluetoothA2dp: Proxy object connected
11-09 11:53:28.134  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:28.134  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:28.134  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:28.134  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:28.134  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:28.134  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:28.134  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:53:28.134  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 11:53:28.135  3052  3052 D BluetoothPan: BluetoothPAN Proxy object connected
11-09 11:53:28.136  3052  3052 D PanProfile: Bluetooth service connected
11-09 11:53:28.136   926   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-09 11:53:28.137  5716  5727 D BluetoothPbap: onBluetoothStateChange: up=true
,11-09 11:53:28.137  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:28.138  5716  5726 D BluetoothA2dp: onBluetoothStateChange: up=true
11-09 11:53:28.139  5823  5823 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-09 11:53:28.139  5823  5823 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-09 11:53:28.140  3052  3067 D BluetoothPbap: onBluetoothStateChange: up=true
11-09 11:53:28.141  5823  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 11:53:28.141  5716  5716 D BluetoothA2dp: Proxy object connected
11-09 11:53:28.142  5716  5727 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 11:53:28.142  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:28.142  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:28.142  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:28.142  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:28.142  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:28.142  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:28.142  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:53:28.142  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 11:53:28.142  3052  3065 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 11:53:28.143   926   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 11:53:28.143  5716  5728 D BluetoothPan: onBluetoothStateChange on: true
11-09 11:53:28.144  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 11:53:28.144  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 21
11-09 11:53:28.145  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Bluetooth enabled, restarting BLE based peer discovery...
11-09 11:53:28.145  3052  3935 D BluetoothMap: onBluetoothStateChange: up=true
11-09 11:53:28.145  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-09 11:53:28.146  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 11:53:28.146  5602  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-09 11:53:28.146  5602  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-09 11:53:28.146   926   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 11:53:28.146  5823  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 11:53:28.146  5716  5727 D BluetoothMap: onBluetoothStateChange: up=true
,11-09 11:53:28.148  5823  5823 D ObexServerSockets: Succeed to create listening sockets 
11-09 11:53:28.148  5823  5823 D ObexServerSockets0: startAccept()
11-09 11:53:28.148  5823  5823 D ObexServerSockets0: prepareForNewConnect()
11-09 11:53:28.149  3052  3067 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-09 11:53:28.150  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-09 11:53:28.150  3052  3052 D BluetoothA2dp: Proxy object connected
11-09 11:53:28.150  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-09 11:53:28.151  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 11:53:28.151  5716  5716 D BluetoothPan: BluetoothPAN Proxy object connected
11-09 11:53:28.151  5716  5716 D PanProfile: Bluetooth service connected
11-09 11:53:28.151  5823  5823 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-09 11:53:28.151  5823  5823 D BluetoothSdpJni: SDP Create record success - handle: 0
11-09 11:53:28.151   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-09 11:53:28.152  5823  5877 D ObexServerSockets0: Accepting socket connection...
11-09 11:53:28.153  5823  5878 D ObexServerSockets0: Accepting socket connection...
,11-09 11:53:28.155  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:28.155  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-09 11:53:28.155  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:28.155  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
,11-09 11:53:28.156  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 11:53:28.156  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.156  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.156  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.156  3052  3052 D BluetoothMap: Proxy object connected
11-09 11:53:28.156  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.156  3052  3052 D MapProfile: Bluetooth service connected
,11-09 11:53:28.156  5823  5823 D BluetoothMapService: onReceive
11-09 11:53:28.156  3052  3052 D BluetoothMap: getConnectedDevices()
11-09 11:53:28.156  5823  5823 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-09 11:53:28.156  5823  5823 D BluetoothMapService: STATE_ON
,11-09 11:53:28.157  5602  5602 D BluetoothAdapter: STATE_ON
,11-09 11:53:28.162  5823  5834 D BtGatt.GattService: registerClient() - UUID=4ce2cf5b-b8bb-4402-bcf8-4f8f65a5c1c8
,11-09 11:53:28.162  5823  5881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 11:53:28.163  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=4ce2cf5b-b8bb-4402-bcf8-4f8f65a5c1c8, clientIf=5
11-09 11:53:28.163  5602  5613 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-09 11:53:28.165  5823  5842 D BtGatt.AdvertiseManager: message : 0
,11-09 11:53:28.165  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-09 11:53:28.165  5823  5881 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-09 11:53:28.165  5823  5881 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-09 11:53:28.167  5716  5716 D BluetoothMap: Proxy object connected
11-09 11:53:28.167  5716  5716 D MapProfile: Bluetooth service connected
11-09 11:53:28.167  5716  5716 D BluetoothMap: getConnectedDevices()
11-09 11:53:28.170  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-09 11:53:28.171  5823  5842 D BtGatt.AdvertiseManager: starting multi advertising
11-09 11:53:28.172  5716  5716 D DockEventReceiver: finishStartingService: stopping service
,11-09 11:53:28.174  5823  5839 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 11:53:28.178  5823  5839 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-09 11:53:28.179  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
,11-09 11:53:28.179  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.179  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:28.179  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.179  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.179  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.179  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.179  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.179  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 11:53:28.180  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 11:53:28.180  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.181  3052  3052 D BluetoothPbap: Proxy object connected
11-09 11:53:28.181  3052  3052 D PbapServerProfile: Bluetooth service connected
11-09 11:53:28.181  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-09 11:53:28.181  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 11:53:28.182  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.182  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.182  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-09 11:53:28.183  5716  5716 D BluetoothPbap: Proxy object connected
11-09 11:53:28.183  5716  5716 D PbapServerProfile: Bluetooth service connected
11-09 11:53:28.184  5823  5823 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-09 11:53:28.184  5823  5823 D ObexServerSockets0: prepareForNewConnect()
,11-09 11:53:28.184  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:28.186  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:28.187  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 12
,11-09 11:53:28.187  5823  5885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 11:53:28.190  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: Bluetooth enabled, restarting BLE based peer discovery...
,11-09 11:53:28.190  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-09 11:53:28.191  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-09 11:53:28.191  5602  5602 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-09 11:53:28.193  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.193  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:28.193  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-09 11:53:28.193  5602  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 11:53:28.193  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.193  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.194  5823  5842 D BtGatt.AdvertiseManager: message : 1
,11-09 11:53:28.195  5823  5842 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-09 11:53:28.204  5823  5839 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 11:53:28.204  5823  5839 D BtGatt.GattService: Client app is not null!
,11-09 11:53:28.205  5823  5889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 11:53:28.205  5823  5879 D BtGatt.GattService: unregisterClient() - clientIf=5
11-09 11:53:28.205  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 11:53:28.206  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.206  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
11-09 11:53:28.206  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.206  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.206  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.206  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.207  5602  5602 D BluetoothAdapter: STATE_ON
11-09 11:53:28.207  5823  5889 I BtOppRfcommListener: Accept thread started.
,11-09 11:53:28.210  5823  5879 D BtGatt.GattService: registerClient() - UUID=7763e70d-4db2-4e26-abf1-c8538d1f8805
,11-09 11:53:28.210  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=7763e70d-4db2-4e26-abf1-c8538d1f8805, clientIf=5
11-09 11:53:28.211  5602  5613 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-09 11:53:28.212  5823  5842 D BtGatt.AdvertiseManager: message : 0
,11-09 11:53:28.217  5823  5842 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 11:53:28.219  5823  5839 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 11:53:28.221  5823  5839 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-09 11:53:28.222  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.222  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
,11-09 11:53:28.222  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:28.222  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.222  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.222  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.222  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.222  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.222  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.222  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Already running
,11-09 11:53:28.222  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.222  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.223  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.223  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 11:53:28.224  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 11:53:28.224  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:28.225  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.225  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.225  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-09 11:53:28.225  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.226  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.226  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 11:53:28.226  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.226  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.226  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.226  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 11:53:28.226  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-09 11:53:28.226  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.226  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.226  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-09 11:53:28.226  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:28.229  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.229  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 11:53:28.229  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.229  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.229  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.229  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-09 11:53:28.229  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 11:53:28.229  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 11:53:28.229  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.229  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:28.229  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-09 11:53:28.232  5602  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:28.232  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:28.232  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:28.232  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:28.232  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:28.232  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:28.232  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:53:28.232  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 11:53:28.233   926   926 D BluetoothHeadset: Proxy object connected
11-09 11:53:28.233  3754  3952 D BluetoothHeadset: Proxy object connected
11-09 11:53:28.234  5602  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:28.234   926   926 D BluetoothHeadset: Proxy object connected
,11-09 11:53:28.234  5716  5727 D BluetoothHeadset: Proxy object connected
,11-09 11:53:28.234  5602  5648 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-09 11:53:28.234  3052  3065 D BluetoothHeadset: Proxy object connected
11-09 11:53:28.235  3052  3052 D HeadsetProfile: Bluetooth service connected
11-09 11:53:28.235   926   926 D BluetoothHeadset: Proxy object connected
,11-09 11:53:28.235   926  3092 D WifiService: setWifiEnabled: false pid=5602, uid=10077
,11-09 11:53:28.235   926  3092 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 11:53:28.236   926  2950 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-09 11:53:28.236   926  2950 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-09 11:53:28.237   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-09 11:53:28.237   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-09 11:53:28.237   926   944 D BluetoothHeadset: Proxy object connected
11-09 11:53:28.239  5602  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:28.241  5716  5716 D HeadsetProfile: Bluetooth service connected
11-09 11:53:28.243  5716  5726 D BluetoothHeadset: Proxy object connected
11-09 11:53:28.243  3052  3935 D BluetoothHeadset: Proxy object connected
,11-09 11:53:28.244  5716  5716 D HeadsetProfile: Bluetooth service connected
11-09 11:53:28.244   926   944 D BluetoothHeadset: Proxy object connected
11-09 11:53:28.248   926  5821 D DhcpClient: Clearing IP address
11-09 11:53:28.246   926   944 D BluetoothHeadset: Proxy object connected
11-09 11:53:28.248   507   919 D CommandListener: Clearing all IP addresses on wlan0
11-09 11:53:28.243  3052  3052 D HeadsetProfile: Bluetooth service connected
,11-09 11:53:28.266  3529  5861 V NativeCrypto: Read error: ssl=0x7f91085700: I/O error during system call, Connection timed out
,11-09 11:53:28.268  3529  5861 V NativeCrypto: SSL shutdown failed: ssl=0x7f91085700: I/O error during system call, Broken pipe
,11-09 11:53:28.270   507   919 D CommandListener: Setting iface cfg
,11-09 11:53:28.270   926  5822 D DhcpClient: Receive thread stopped
,11-09 11:53:28.271   926  3784 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-09 11:53:28.273   926  5818 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-09 11:53:28.273   926  5818 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-09 11:53:28.278   926  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-09 11:53:28.279   926  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-09 11:53:28.281   926   926 D RttService: SCAN_AVAILABLE : 1
11-09 11:53:28.282   926  3019 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-09 11:53:28.284   533   533 E Parcel  : Reading a NULL string not supported here.
,11-09 11:53:28.284   926  2954 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-09 11:53:28.285   926  5818 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-09 11:53:28.285  3708  3826 W QCNEJ   : |CORE| network lost: 101
11-09 11:53:28.286  3708  3826 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-09 11:53:28.306   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 11:53:28.322   926  2950 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-09 11:53:28.323   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-09 11:53:28.333   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-09 11:53:28.333   507   919 D CommandListener: Clearing all IP addresses on wlan0
11-09 11:53:28.333   926  2954 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-09 11:53:28.333   926  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-09 11:53:28.336   926  2950 D DhcpClient: doQuit
,11-09 11:53:28.336   926  2950 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-09 11:53:28.336   926  5821 D DhcpClient: onQuitting
11-09 11:53:28.337   926   944 D Tethering: MasterInitialState.processMessage what=3
11-09 11:53:28.337  5703  5703 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-09 11:53:28.338  3908  3908 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-09 11:53:28.342  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:28.342  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:28.342  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:28.342  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:28.342  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:28.342  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:28.342  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:28.342  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 11:53:28.344  3922  3922 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-09 11:53:28.345  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-09 11:53:28.347  3922  3922 D SystemUpdateService: onCreate
,11-09 11:53:28.349  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:28.349  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:28.349  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:28.349  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 11:53:28.349  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:28.349  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:28.349  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:28.349  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 11:53:28.350  3922  3922 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-09 11:53:28.351  5703  5703 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-09 11:53:28.352  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:28.355  5703  5703 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-09 11:53:28.356  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:28.356  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:28.356  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:28.356  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 11:53:28.356  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:28.356  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:28.356  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:28.356  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:28.358  3922  5897 I SystemUpdateService: active receiver: enabled
,11-09 11:53:28.359  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:28.361  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:28.361  3922  3922 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-09 11:53:28.366  3922  4269 I iu.UploadsManager: num queued entries: 0
,11-09 11:53:28.366  3922  4269 I iu.UploadsManager: num updated entries: 0
11-09 11:53:28.366  3922  4269 I iu.SyncManager: NEXT; no task
,11-09 11:53:28.369  3922  3922 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-09 11:53:28.370  3922  3922 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-09 11:53:28.372  5379  5379 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-09 11:53:28.377  5379  5379 D SprintDMHelper: simOperator: 
,11-09 11:53:28.377  5379  5379 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-09 11:53:28.388  3922  5897 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-09 11:53:28.393  5703  5703 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-09 11:53:28.394  3922  5897 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-09 11:53:28.394  3922  5897 I SystemUpdateService: now status is 0 (complete)
11-09 11:53:28.394  3922  5897 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-09 11:53:28.395   507   919 E Netd    : netlink response contains error (No such file or directory)
,11-09 11:53:28.395  3922  5897 I SystemUpdateService: file has been verified
11-09 11:53:28.396  3922  5897 I SystemUpdateService: OTA package size = 21989297
,11-09 11:53:28.396   926  2954 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-09 11:53:28.401  5703  5703 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-09 11:53:28.402   926  2954 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-09 11:53:28.411  3922  5897 I SystemUpdateService: showing system update notification
,11-09 11:53:28.417   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-09 11:53:28.418  3922  3922 D SystemUpdateService: onDestroy
,11-09 11:53:28.507   926  2950 D wifi    : In wifi stop Hal
,11-09 11:53:28.507  4396  4396 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-09 11:53:28.507   926  2950 D wifi    : halHandle = 0x7f8ee1eb80, mVM = 0x7fab44d140, mCls = 0x17ea
11-09 11:53:28.507   926  5702 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-09 11:53:28.507   926  5702 D WifiHAL : Got a signal to exit!!!
,11-09 11:53:28.507   926  5702 I WifiHAL : Exit wifi_event_loop
11-09 11:53:28.508   926  2950 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-09 11:53:28.508   926  2950 E WifiHAL : Event processing terminated
11-09 11:53:28.508   926  2950 D wifi    : In wifi cleaned up handler
11-09 11:53:28.508   926  2950 I WifiHAL : Internal cleanup completed
,11-09 11:53:28.509  4063  4176 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-09 11:53:28.510  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:28.511  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:28.531   926  5702 D wifi    : set interface wlan0 flags (DOWN)
,11-09 11:53:28.532   926  2950 D WifiNative-HAL: HAL event thread stopped successfully
,11-09 11:53:28.594   507   919 E Netd    : netlink response contains error (No such file or directory)
,11-09 11:53:28.730  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-09 11:53:28.739   926   944 D Tethering: InitialState.processMessage what=4
,11-09 11:53:28.746   926   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
11-09 11:53:28.746  5602  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:28.746  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:28.746  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:28.746  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 11:53:28.746  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:28.746  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:28.746  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:28.746  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 11:53:28.751  5602  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:28.753   926  3367 D WifiService: setWifiEnabled: true pid=5602, uid=10077
11-09 11:53:28.753   926  3367 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-09 11:53:28.754  5602  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:28.758   507   919 D SoftapController: Softap fwReload - Ok
,11-09 11:53:28.762   507   919 D CommandListener: Setting iface cfg
,11-09 11:53:28.763   507   919 D CommandListener: Trying to bring down wlan0
11-09 11:53:28.764   507   919 D CommandListener: Clearing all IP addresses on wlan0
,11-09 11:53:28.770   926  2950 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-09 11:53:29.257   926  3092 D WifiService: setWifiEnabled: true pid=5602, uid=10077
,11-09 11:53:29.258   926  3092 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 11:53:29.368   926  2950 D wifi    : set interface wlan0 flags (UP)
,11-09 11:53:29.368   926  2950 I WifiHAL : Initializing wifi
,11-09 11:53:29.369   926  2950 I WifiHAL : Creating socket
,11-09 11:53:29.375   926  2950 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-09 11:53:29.375   926  2950 D wifi    : Did set static halHandle = 0x7f8ee1eb80
,11-09 11:53:29.375   926  2950 D wifi    : halHandle = 0x7f8ee1eb80, mVM = 0x7fab44d140, mCls = 0x1976
11-09 11:53:29.376   926  2950 D wifi    : array field set
11-09 11:53:29.376   926  2950 I WifiNative-HAL: interface[0] = wlan0
11-09 11:53:29.379   926  5914 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547858017152
11-09 11:53:29.379   926  5914 D wifi    : waitForHalEvents called, vm = 0x7fab44d140, obj = 0x1976, env = 0x7f935bff40
,11-09 11:53:29.388   926  2950 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-09 11:53:29.390   926  2950 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-09 11:53:29.392  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:29.394  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:29.401   926   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-09 11:53:29.442  5915  5915 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-09 11:53:29.513  5915  5915 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-09 11:53:29.522  5915  5915 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-09 11:53:29.522  5915  5915 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-09 11:53:29.761   926  3784 D WifiService: setWifiEnabled: true pid=5602, uid=10077
,11-09 11:53:29.761   926  3784 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 11:53:30.266   926   936 D WifiService: setWifiEnabled: true pid=5602, uid=10077
,11-09 11:53:30.266   926   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 11:53:30.408   926  2950 D WifiConfigStore: Loading config and enabling all networks 
,11-09 11:53:30.416  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:30.416  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:30.416  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:30.416  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:30.416  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:30.416  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:30.416  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:30.416  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:30.422  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:30.429  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:30.429  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:30.429  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:30.429  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:30.429  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:30.429  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:30.429  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:30.429  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 11:53:30.432  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:30.447   926  2950 D WifiConfigStore: loaded 0 passpoint configs
,11-09 11:53:30.448   926  2950 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-09 11:53:30.448   926  2950 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-09 11:53:30.449   926  2950 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-09 11:53:30.449   926  2950 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-09 11:53:30.450   926  2950 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-09 11:53:30.451   926  2950 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-09 11:53:30.451   926  2950 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-09 11:53:30.451   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-09 11:53:30.451   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-09 11:53:30.452   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-09 11:53:30.452   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-09 11:53:30.452   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-09 11:53:30.455   926  2950 D WifiNative-HAL: Setting external_sim to 1
,11-09 11:53:30.455  4396  4396 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-09 11:53:30.456   926  2950 D wifi    : setting dfs flag to true, 0x7f9348ce60
11-09 11:53:30.457   926  2950 D WifiStateMachine: Setting OUI to DA-A1-19
,11-09 11:53:30.457   926  2950 D wifi    : setting scan oui 0x7f9348ce60
11-09 11:53:30.457   926  2950 D WifiHAL : Sending mac address OUI
,11-09 11:53:30.461   926  2950 E native  : do suspend false
,11-09 11:53:30.470   926  2950 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-09 11:53:30.470   507   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-09 11:53:30.470   926   926 D RttService: SCAN_AVAILABLE : 3
11-09 11:53:30.471   926  3019 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-09 11:53:30.471   507   919 D CommandListener: Setting iface cfg
,11-09 11:53:30.475   926  2949 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
11-09 11:53:30.475   926  2949 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-09 11:53:30.486   926  2949 D WifiNative-HAL: p2pGetDeviceAddress
,11-09 11:53:30.487   926  2949 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-09 11:53:30.492   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=111198 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-09 11:53:30.776  5602  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:30.776  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:30.776  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:30.776  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:30.776  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:30.776  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:30.776  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:30.776  5602  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 11:53:30.785  5602  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:30.788  5602  5648 D BluetoothAdapter: enable(): BT is already enabled..!
,11-09 11:53:30.789   926  3784 D WifiService: setWifiEnabled: true pid=5602, uid=10077
11-09 11:53:30.789   926  3784 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 11:53:30.790  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-09 11:53:30.790  5602  5648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-09 11:53:30.791  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-09 11:53:30.791  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-09 11:53:30.791  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-09 11:53:30.791  5602  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f93656e removed from the list
11-09 11:53:30.791  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-09 11:53:30.791  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbde40f removed from the list
11-09 11:53:30.791  5602  5648 D io.jxcore.node.ConnectivityMonitor: stop
11-09 11:53:30.791  5602  5648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-09 11:53:30.791  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-09 11:53:30.795  5602  5648 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-09 11:53:30.797  5602  5648 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-09 11:53:30.799  5602  5648 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-09 11:53:30.800  5602  5648 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-09 11:53:30.804  5602  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-09 11:53:30.806  5602  5648 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-09 11:53:30.808  5602  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-09 11:53:30.808  5602  5648 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-09 11:53:30.809  5602  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
11-09 11:53:30.812  5602  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-09 11:53:30.812  5602  5648 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@cd4ad63 Bundle[{}]
11-09 11:53:30.813  5602  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,11-09 11:53:30.813  5602  5648 I io.jxcore.node.LifeCycleMonitor: start: OK
11-09 11:53:30.813  5602  5648 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-09 11:53:30.814  5602  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-09 11:53:30.814  5602  5648 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-09 11:53:30.815  5602  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-09 11:53:30.815  5602  5648 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-09 11:53:30.816  5602  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,11-09 11:53:30.816  5602  5648 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-09 11:53:30.817  5602  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-09 11:53:30.817  5602  5648 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-09 11:53:30.819  5602  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-09 11:53:30.820  5602  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-09 11:53:30.821  5602  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-09 11:53:30.822  5602  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-09 11:53:30.823  5602  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-09 11:53:30.824  5602  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-09 11:53:30.825  5602  5648 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
11-09 11:53:30.826  5602  5648 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-09 11:53:30.827  5602  5648 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-09 11:53:30.829  5602  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-09 11:53:30.829  5602  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-09 11:53:30.830  5602  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-09 11:53:30.831  5602  5648 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 140)
11-09 11:53:30.831  5602  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-09 11:53:30.831  5602  5648 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-09 11:53:30.832  5602  5648 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
11-09 11:53:30.832  5602  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-09 11:53:30.832  5602  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-09 11:53:30.833  5602  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-09 11:53:30.833  5602  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-09 11:53:30.833  5602  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47d2688 added. We now have 3 listener(s)
11-09 11:53:30.835  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:30.835  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-09 11:53:30.835  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-09 11:53:30.835  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-09 11:53:30.835  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@370821 added. We now have 3 listener(s)
11-09 11:53:30.835  5602  5648 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-09 11:53:30.836  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-09 11:53:30.838  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 11:53:30.841  5602  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 11:53:30.841  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:30.841  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:30.841  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:30.841  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:30.841  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 11:53:30.841  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 11:53:30.841  5602  5648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 11:53:30.843  5602  5648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 11:53:30.844  5602  5648 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-09 11:53:30.847  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:53:30.848  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:53:30.848  5602  5648 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-09 11:53:30.849  5602  5648 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,11-09 11:53:30.849  5602  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,11-09 11:53:30.849  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-09 11:53:30.850  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 11:53:30.850  5602  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-09 11:53:30.850  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-09 11:53:30.850  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 11:53:30.851  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-09 11:53:30.852  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-09 11:53:30.852  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-09 11:53:30.852  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-09 11:53:30.852  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-09 11:53:30.852  5602  5926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-09 11:53:30.852  5602  5602 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-09 11:53:30.852  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-09 11:53:30.852  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 11:53:30.852  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-09 11:53:30.853  5602  5926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 11:53:30.854  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 11:53:30.851  5834  5834 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32352]" dev="sockfs" ino=32352 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 11:53:30.854  5602  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-09 11:53:30.854  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-09 11:53:30.855  5602  5926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-09 11:53:30.851  5834  5834 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32352]" dev="sockfs" ino=32352 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-09 11:53:30.859  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-09 11:53:30.860  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-09 11:53:30.860  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 11:53:30.862  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.862  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 11:53:30.863  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:30.863  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-09 11:53:30.863  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 11:53:30.863  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.863  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.863  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:30.863  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.864  5602  5648 D BluetoothAdapter: STATE_ON
11-09 11:53:30.867  5823  5876 D BtGatt.GattService: registerClient() - UUID=d9f46e38-1cad-4d20-bcfb-c4074e2a303a
11-09 11:53:30.867  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=d9f46e38-1cad-4d20-bcfb-c4074e2a303a, clientIf=6
11-09 11:53:30.868  5602  5613 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-09 11:53:30.869  5823  5842 D BtGatt.AdvertiseManager: message : 0
11-09 11:53:30.871  5823  5842 D BtGatt.AdvertiseManager: starting multi advertising
11-09 11:53:30.882  5823  5839 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
11-09 11:53:30.888  5823  5839 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
11-09 11:53:30.889  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.889  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.889  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:30.889  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.890  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.890  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.890  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.890  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.890  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 11:53:30.892  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 11:53:30.892  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:30.893  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.893  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.893  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:30.893  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 11:53:30.894  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 11:53:30.894  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:30.894  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 11:53:30.894  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 11:53:30.894  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:30.894  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:30.894  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 11:53:30.894  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-09 11:53:30.894  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:30.894  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-09 11:53:30.894  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-09 11:53:30.894  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:30.897  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:30.897  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 11:53:30.897  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:30.897  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:30.898  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:30.898  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:30.898  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-09 11:53:31.399  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-09 11:53:31.399  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-09 11:53:31.399  5602  5602 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-09 11:53:33.529   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-09 11:53:33.530   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-09 11:53:33.581  5915  5915 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 11:53:33.589  5915  5915 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 11:53:33.594  5915  5915 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 11:53:33.600  5915  5915 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 11:53:33.623   926  2950 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-09 11:53:33.624   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-09 11:53:33.624   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 11:53:33.637   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-09 11:53:33.673   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-09 11:53:33.679  5915  5915 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-09 11:53:34.099  5915  5915 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-09 11:53:34.134  5915  5915 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-09 11:53:34.136  5915  5915 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-09 11:53:34.144   926  2950 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-09 11:53:34.144   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-09 11:53:34.144   926  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-09 11:53:34.163   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 11:53:34.177   507   919 D CommandListener: Setting iface cfg
,11-09 11:53:34.182   926  2950 D WifiStateMachine: Start Dhcp Watchdog 3
,11-09 11:53:34.187   926  5931 D DhcpClient: Receive thread started
,11-09 11:53:34.191   926  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-09 11:53:34.191   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-09 11:53:34.191   926  2954 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-09 11:53:34.271   926  2950 E native  : do suspend false
,11-09 11:53:34.281   926  5930 D DhcpClient: Broadcasting DHCPDISCOVER
,11-09 11:53:34.294   926  5931 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172793, domain null
,11-09 11:53:34.295   926  5930 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172793 seconds
,11-09 11:53:34.297   926  5930 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-09 11:53:34.310   926  5931 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-09 11:53:34.311   926  5930 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-09 11:53:34.314   507   919 D CommandListener: Setting iface cfg
11-09 11:53:34.319   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-09 11:53:34.323   926  5930 D DhcpClient: Scheduling renewal in 86399s
,11-09 11:53:34.337   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-09 11:53:34.339   926  2950 D WifiConfigStore: No blacklist allowed without epno enabled
,11-09 11:53:34.343   926  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-09 11:53:34.347   926  2950 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-09 11:53:34.347   926  2954 D ConnectivityService: Adding iface wlan0 to network 102
,11-09 11:53:34.395  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-09 11:53:34.396  5602  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-09 11:53:34.396  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-09 11:53:34.396  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-09 11:53:34.396  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-09 11:53:34.396  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
11-09 11:53:34.396  5602  5926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-09 11:53:34.396  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-09 11:53:34.396  5602  5926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-09 11:53:34.396  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-09 11:53:34.396  5602  5926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-09 11:53:34.397  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-09 11:53:34.397  5602  5602 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-09 11:53:34.397  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-09 11:53:34.397  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-09 11:53:34.397  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-09 11:53:34.397  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.397  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.399  5602  5648 D BluetoothAdapter: STATE_ON
11-09 11:53:34.399  5602  5648 D BluetoothLeScanner: could not find callback wrapper
11-09 11:53:34.399  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-09 11:53:34.399  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.399  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:34.399  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-09 11:53:34.399  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:34.401  5823  5842 D BtGatt.AdvertiseManager: message : 1
11-09 11:53:34.401   926  2954 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-09 11:53:34.401   926  2954 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-09 11:53:34.402  5823  5842 D BtGatt.AdvertiseManager: stop advertise for client 6
11-09 11:53:34.404   926  2954 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-09 11:53:34.406   926  2954 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
11-09 11:53:34.411   926  2954 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
11-09 11:53:34.412  5823  5839 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-09 11:53:34.412  5823  5839 D BtGatt.GattService: Client app is not null!
,11-09 11:53:34.414  5823  5868 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-09 11:53:34.415  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 11:53:34.415  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.415  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-09 11:53:34.416  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.416  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.416  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.416  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-09 11:53:34.416  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-09 11:53:34.416  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.416  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.416  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-09 11:53:34.416  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:34.419  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:34.420  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 11:53:34.421  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.421  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.421  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.421  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.421  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.421  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-09 11:53:34.421  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,11-09 11:53:34.421  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-09 11:53:34.421  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:34.422   926  2954 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-09 11:53:34.424  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.424  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.425  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.425  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-09 11:53:34.425  5602  5602 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-09 11:53:34.425  5602  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-09 11:53:34.425  5602  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-09 11:53:34.425  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 11:53:34.425  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 11:53:34.427  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 11:53:34.427  5602  5648 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-09 11:53:34.427  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-09 11:53:34.428   926  2954 D ConnectivityService: scheduleUnvalidatedPrompt 102
11-09 11:53:34.428  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-09 11:53:34.428  5602  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-09 11:53:34.428   926  2954 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-09 11:53:34.428  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-09 11:53:34.428  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 11:53:34.428   926  2954 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-09 11:53:34.428  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-09 11:53:34.428   926  2954 D ConnectivityService:    accepting network in place of null
11-09 11:53:34.428   926  2950 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-09 11:53:34.428   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-09 11:53:34.429  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-09 11:53:34.429   926  2954 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-09 11:53:34.429  5602  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-09 11:53:34.429  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-09 11:53:34.433  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-09 11:53:34.434  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-09 11:53:34.434  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-09 11:53:34.438  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:34.438  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-09 11:53:34.439  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-09 11:53:34.439  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-09 11:53:34.439  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-09 11:53:34.439  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.439   926  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=115145, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-09 11:53:34.440  5602  5648 D BluetoothAdapter: STATE_ON
,11-09 11:53:34.443  5823  5834 D BtGatt.GattService: registerClient() - UUID=0d67a6b0-fed8-4eb6-ab14-5dd0b92f3bca
,11-09 11:53:34.443  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=0d67a6b0-fed8-4eb6-ab14-5dd0b92f3bca, clientIf=6
11-09 11:53:34.443  5602  5649 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,11-09 11:53:34.444  5823  5879 D BtGatt.GattService: start scan with filters
,11-09 11:53:34.449  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-09 11:53:34.449  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.449  5823  5844 D BtGatt.ScanManager: handling starting scan
11-09 11:53:34.449  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-09 11:53:34.449  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.449  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.450  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-09 11:53:34.450  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-09 11:53:34.450  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.450  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.450  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-09 11:53:34.450  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.450  5823  5844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f8a5f4
,11-09 11:53:34.452  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.452  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-09 11:53:34.452  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.452  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-09 11:53:34.452  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.452  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.452  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 11:53:34.454  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 11:53:34.454  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.456  5823  5839 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,11-09 11:53:34.456  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-09 11:53:34.456  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.456  5823  5844 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-09 11:53:34.456  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.456  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:34.457   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 11:53:34.461  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=31
,11-09 11:53:34.461  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-09 11:53:34.462  5823  5844 D BtGatt.ScanManager: Starting BLE batch scan
11-09 11:53:34.462  5823  5844 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,11-09 11:53:34.469  5823  5839 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
11-09 11:53:34.469  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,11-09 11:53:34.474  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,11-09 11:53:34.474  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,11-09 11:53:34.478   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 11:53:34.483   926  2954 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-09 11:53:34.483   926  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-09 11:53:34.483  3708  3826 W QCNEJ   : |CORE| network available: 102
11-09 11:53:34.484   926  2954 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-09 11:53:34.485   926   944 D Tethering: MasterInitialState.processMessage what=3
,11-09 11:53:34.485  3708  3826 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-09 11:53:34.488  3708  3826 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-09 11:53:34.488  3708  3826 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-09 11:53:34.492  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:34.492  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:34.492  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:34.492  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:34.492  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:34.492  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:34.492  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:53:34.492  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 11:53:34.495  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 11:53:34.497  3908  3908 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-09 11:53:34.498  3922  3922 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-09 11:53:34.499  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:34.499  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:34.499  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:34.499  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:34.499  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:34.499  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:34.499  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:53:34.499  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 11:53:34.500  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:34.501  3922  3922 D SystemUpdateService: onCreate
,11-09 11:53:34.504  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 11:53:34.504  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:53:34.504  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:53:34.504  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:53:34.504  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:53:34.504  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:53:34.504  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:53:34.504  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 11:53:34.505  3922  3922 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-09 11:53:34.507  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 11:53:34.514  3922  3922 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-09 11:53:34.519  3922  4269 I iu.UploadsManager: num queued entries: 0
,11-09 11:53:34.519  3922  4269 I iu.UploadsManager: num updated entries: 0
11-09 11:53:34.520  3922  4269 I iu.SyncManager: NEXT; no task
,11-09 11:53:34.521  3922  5941 I SystemUpdateService: active receiver: enabled
,11-09 11:53:34.524  3922  3922 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-09 11:53:34.525  3922  3922 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-09 11:53:34.526  5379  5379 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-09 11:53:34.530  5379  5379 D SprintDMHelper: simOperator: 
,11-09 11:53:34.530  5379  5379 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-09 11:53:34.551  3922  5941 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-09 11:53:34.557  3922  5941 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-09 11:53:34.557  3922  5941 I SystemUpdateService: now status is 0 (complete)
11-09 11:53:34.557  3922  5941 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-09 11:53:34.557  3922  5941 I SystemUpdateService: file has been verified
11-09 11:53:34.557  3922  5941 I SystemUpdateService: OTA package size = 21989297
,11-09 11:53:34.562  3922  5941 I SystemUpdateService: showing system update notification
,11-09 11:53:34.569   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-09 11:53:34.571  3922  3922 D SystemUpdateService: onDestroy
,11-09 11:53:34.591   926  5928 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-09 11:53:34.816   926  5928 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Nov 2016 10:53:34 GMT], X-Android-Received-Millis=[1478688814812], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478688814613]}
,11-09 11:53:34.818   926  2954 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-09 11:53:34.818   926  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-09 11:53:34.819   926  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-09 11:53:34.822   926  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-09 11:53:34.952  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-09 11:53:34.952  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-09 11:53:34.953  5602  5602 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-09 11:53:34.977  5823  5823 D BtGatt.ScanManager: awakened up at time 115683
,11-09 11:53:34.981  5823  5844 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,11-09 11:53:35.006  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=3
,11-09 11:53:35.006  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-09 11:53:35.006  5823  5839 D BtGatt.GattService: current time is 115712882716
11-09 11:53:35.007  5823  5839 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
,11-09 11:53:35.012  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-09 11:53:35.014  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-09 11:53:35.014  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,11-09 11:53:35.019  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
,11-09 11:53:35.019  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-09 11:53:35.019  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=115663854435}
,11-09 11:53:35.019  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-09 11:53:35.020  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=115413854435}
11-09 11:53:35.021  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-09 11:53:35.021  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=115413854435}
,11-09 11:53:35.243   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,11-09 11:53:35.255   926  2954 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-09 11:53:35.261  3708  3826 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-09 11:53:35.261  3708  3826 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-09 11:53:35.360   926  2954 D ConnectivityService: handlePromptUnvalidated 101
,11-09 11:53:35.509  5823  5823 D BtGatt.ScanManager: awakened up at time 116215
,11-09 11:53:35.513  5823  5844 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,11-09 11:53:35.537  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,11-09 11:53:35.537  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,11-09 11:53:35.538  5823  5839 D BtGatt.GattService: current time is 116244217675
11-09 11:53:35.538  5823  5839 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -74, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-09 11:53:35.539  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-09 11:53:35.540  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
11-09 11:53:35.542  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-09 11:53:35.542  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-74, mTimestampNanos=116194694594}
,11-09 11:53:37.213   926  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-09 11:53:37.459  5602  5648 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-09 11:53:37.459  5602  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-09 11:53:37.459  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,11-09 11:53:37.460  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-09 11:53:37.460  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-09 11:53:37.460  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-09 11:53:37.460  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-09 11:53:37.460  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-09 11:53:37.460  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-09 11:53:37.460  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-09 11:53:37.460  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-09 11:53:37.460  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-09 11:53:37.460  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-09 11:53:37.461  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-09 11:53:37.463  5602  5648 D BluetoothAdapter: STATE_ON
11-09 11:53:37.465  5823  5880 D BtGatt.GattService: stopScan() - queue size =1
11-09 11:53:37.466  5823  5833 D BtGatt.GattService: unregisterClient() - clientIf=6
11-09 11:53:37.467  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-09 11:53:37.467  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:37.468  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-09 11:53:37.468  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 11:53:37.468  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.468  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-09 11:53:37.468  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-09 11:53:37.468  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-09 11:53:37.469  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-09 11:53:37.469  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.471  5602  5648 D BluetoothAdapter: STATE_ON
11-09 11:53:37.479  5823  5823 D BtGatt.ScanManager: awakened up at time 118185
11-09 11:53:37.479  5823  5834 D BtGatt.GattService: registerClient() - UUID=9d10d8d5-595b-4207-9322-9a4fb0f96983
11-09 11:53:37.481  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=9d10d8d5-595b-4207-9322-9a4fb0f96983, clientIf=6
,11-09 11:53:37.482  5602  5613 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
11-09 11:53:37.482  5823  5868 D BtGatt.GattService: start scan with filters
,11-09 11:53:37.485  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=32
,11-09 11:53:37.485  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-09 11:53:37.485  5823  5844 D BtGatt.ScanManager: stopping BLe Batch
,11-09 11:53:37.488  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-09 11:53:37.489  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.489  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-09 11:53:37.489  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.489  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.489  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-09 11:53:37.489  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-09 11:53:37.489  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.489  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.490  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-09 11:53:37.490  5602  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-09 11:53:37.490  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-09 11:53:37.490  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 11:53:37.491  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-09 11:53:37.491  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
11-09 11:53:37.491  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-09 11:53:37.491  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-09 11:53:37.491  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-09 11:53:37.491  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-09 11:53:37.491  5823  5844 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
11-09 11:53:37.491  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-09 11:53:37.491  5602  5602 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-09 11:53:37.492  5602  5949 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-09 11:53:37.492  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-09 11:53:37.493  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 11:53:37.493  5602  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-09 11:53:37.491  5834  5834 W Binder_2: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[34517]" dev="sockfs" ino=34517 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 11:53:37.491  5834  5834 W Binder_2: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[34517]" dev="sockfs" ino=34517 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 11:53:37.495  5602  5949 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 11:53:37.497  5602  5949 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-09 11:53:37.500  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:37.500  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.500  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 11:53:37.500  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 11:53:37.501  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-09 11:53:37.501  5602  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 11:53:37.501  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.501  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:37.501  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.501  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.501  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
11-09 11:53:37.501  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-09 11:53:37.501  5823  5839 D BtGatt.GattService: current time is 118207822274
11-09 11:53:37.501  5823  5839 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -93, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
11-09 11:53:37.502  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-09 11:53:37.502  5602  5648 D BluetoothAdapter: STATE_ON
11-09 11:53:37.502  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-09 11:53:37.503  5823  5844 D BtGatt.ScanManager: handling starting scan
11-09 11:53:37.505  5823  5866 D BtGatt.GattService: registerClient() - UUID=6c51580f-f066-4414-9ba0-bd7264d3e06a
,11-09 11:53:37.505  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=6c51580f-f066-4414-9ba0-bd7264d3e06a, clientIf=7
11-09 11:53:37.506  5602  5612 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
11-09 11:53:37.506  5823  5842 D BtGatt.AdvertiseManager: message : 0
11-09 11:53:37.509  5823  5839 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,11-09 11:53:37.509  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-09 11:53:37.509  5823  5844 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-09 11:53:37.511  5823  5842 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 11:53:37.514  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=31
,11-09 11:53:37.514  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-09 11:53:37.514  5823  5844 D BtGatt.ScanManager: Starting BLE batch scan
11-09 11:53:37.515  5823  5844 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,11-09 11:53:37.523  5823  5839 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,11-09 11:53:37.531  5823  5839 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,11-09 11:53:37.531  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,11-09 11:53:37.535  5823  5839 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,11-09 11:53:37.536  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.536  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.536  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 11:53:37.536  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.536  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.536  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.536  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.536  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.537  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.537  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.537  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.537  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-09 11:53:37.537  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-09 11:53:37.537  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-09 11:53:37.538  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 11:53:37.539  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:37.540  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
11-09 11:53:37.540  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,11-09 11:53:37.541  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:37.541  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.542  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:37.542  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-09 11:53:37.542  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 11:53:37.542  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:37.542  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 11:53:37.542  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
,11-09 11:53:37.542  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:37.542  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 11:53:37.542  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
,11-09 11:53:37.542  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-09 11:53:37.543  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 11:53:37.543  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-09 11:53:37.543  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-09 11:53:37.543  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 11:53:37.545  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 11:53:37.545  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-09 11:53:37.545  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-09 11:53:37.545  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 11:53:37.545  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 11:53:37.546  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 11:53:37.546  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-09 11:53:38.047  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-09 11:53:38.047  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-09 11:53:38.047  5602  5602 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-09 11:53:38.504   926  2950 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 11 -> obsolete
,11-09 11:53:38.531   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:39.370   926  2950 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 11 -> obsolete
,11-09 11:53:39.532   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:40.533   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:40.545  5602  5648 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-09 11:53:40.546  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-09 11:53:40.546  5602  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-09 11:53:40.546  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-09 11:53:40.546  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-09 11:53:40.547  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
11-09 11:53:40.547  5602  5949 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-09 11:53:40.547  5602  5949 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-09 11:53:40.547  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-09 11:53:40.547  5602  5949 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-09 11:53:40.547  5602  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-09 11:53:40.548  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-09 11:53:40.548  5602  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-09 11:53:40.548  5602  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-09 11:53:40.548  5602  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47d2688 removed from the list
11-09 11:53:40.548  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-09 11:53:40.548  5602  5602 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-09 11:53:40.548  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-09 11:53:40.549  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-09 11:53:40.549  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-09 11:53:40.549  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.549  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:40.550  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-09 11:53:40.553  5602  5648 D BluetoothAdapter: STATE_ON
,11-09 11:53:40.556  5823  5834 D BtGatt.GattService: stopScan() - queue size =1
,11-09 11:53:40.559  5823  5876 D BtGatt.GattService: unregisterClient() - clientIf=6
11-09 11:53:40.560  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-09 11:53:40.561  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:40.561  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-09 11:53:40.562  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.562  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.562  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 11:53:40.562  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-09 11:53:40.563  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.563  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:40.563  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-09 11:53:40.563  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.565  5823  5823 D BtGatt.ScanManager: awakened up at time 121271
,11-09 11:53:40.569  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.569  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=32
11-09 11:53:40.569  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,11-09 11:53:40.569  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 11:53:40.569  5823  5844 D BtGatt.ScanManager: stopping BLe Batch
11-09 11:53:40.569  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.569  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.569  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.569  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:40.570  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-09 11:53:40.570  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.571  5823  5842 D BtGatt.AdvertiseManager: message : 1
11-09 11:53:40.572  5823  5842 D BtGatt.AdvertiseManager: stop advertise for client 7
,11-09 11:53:40.575  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,11-09 11:53:40.575  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-09 11:53:40.576  5823  5844 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,11-09 11:53:40.580  5823  5839 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,11-09 11:53:40.580  5823  5839 D BtGatt.GattService: Client app is not null!
,11-09 11:53:40.581  5823  5868 D BtGatt.GattService: unregisterClient() - clientIf=7
,11-09 11:53:40.582  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 11:53:40.582  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:40.582  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-09 11:53:40.582  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:40.582  5602  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:40.582  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.583  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-09 11:53:40.583  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-09 11:53:40.583  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.583  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.583  5602  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-09 11:53:40.583  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.584  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-09 11:53:40.584  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 11:53:40.585  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.585  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.585  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.585  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.585  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.585  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-09 11:53:40.585  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,11-09 11:53:40.585  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-09 11:53:40.586  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.587  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.588  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.588  5602  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-09 11:53:40.588  5602  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@370821 removed from the list
11-09 11:53:40.588  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 11:53:40.588  5602  5648 D io.jxcore.node.ConnectivityMonitor: stop
,11-09 11:53:40.588  5602  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-09 11:53:40.588  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 11:53:40.588  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 11:53:40.588  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 11:53:40.589  5602  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-09 11:53:40.590  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-09 11:53:40.590  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-09 11:53:40.590  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-09 11:53:40.590  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-09 11:53:40.590  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,11-09 11:53:40.590  5602  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-09 11:53:40.591  5602  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-09 11:53:40.592  5602  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-09 11:53:40.593  5602  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,11-09 11:53:40.593  5602  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,11-09 11:53:40.594  5602  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,11-09 11:53:40.595  5602  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-09 11:53:40.596  5602  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-09 11:53:40.596  5602  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-09 11:53:40.604  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=6
,11-09 11:53:40.604  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-09 11:53:40.605  5823  5839 D BtGatt.GattService: current time is 121311048834
11-09 11:53:40.605  5823  5839 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -84, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -82, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -84, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -76, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
11-09 11:53:40.605  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-09 11:53:40.605  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-09 11:53:40.605  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-09 11:53:40.606  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-09 11:53:40.606  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-09 11:53:40.606  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,11-09 11:53:41.089  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-09 11:53:41.534   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:42.433   926  2954 D ConnectivityService: handlePromptUnvalidated 102
,11-09 11:53:42.535   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:42.601  5602  5648 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-09 11:53:42.725  5602  5951 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-09 11:53:42.725  5602  5951 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 11:53:43.524  5602  5951 W !!      : call onHalfStreamCopied
,11-09 11:53:43.524  5602  5951 I testCopyDataAndClose: closing input stream
,11-09 11:53:43.535   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-09 11:53:44.296  5602  5951 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-09 11:53:44.296  5602  5951 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 11:53:44.296  5602  5951 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-09 11:53:44.296  5602  5951 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-09 11:53:44.296  5602  5951 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-09 11:53:44.296  5602  5951 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-09 11:53:44.296  5602  5951 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-09 11:53:44.296  5602  5951 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-09 11:53:44.296  5602  5951 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-09 11:53:44.296  5602  5951 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-09 11:53:44.296  5602  5951 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-09 11:53:44.323  3635  3811 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-09 11:53:44.323  3635  3811 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-09 11:53:44.343  3529  3529 I ConfigService: onCreate
,11-09 11:53:45.487   926  2950 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-09 11:53:47.349   926  2950 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,11-09 11:53:48.536   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:48.844  5602  5648 I StreamCopyingThreadTest: Starting test: testRun
,11-09 11:53:48.848  5602  5953 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: My test thread name). Connection data: Peer properties: [null null].
11-09 11:53:48.848  5602  5953 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 11:53:49.371  3529  3529 I ConfigService: onDestroy
,11-09 11:53:49.537   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:50.539   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:51.541   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:52.542   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:53:53.543   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-09 11:53:53.856  5602  5954 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-09 11:53:53.859  5602  5648 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-09 11:53:54.005  5602  5955 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-09 11:53:54.005  5602  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 11:53:55.640  5602  5955 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-09 11:53:55.640  5602  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 11:53:55.640  5602  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-09 11:53:55.640  5602  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 11:53:55.640  5602  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-09 11:53:55.640  5602  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-09 11:53:55.640  5602  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-09 11:53:55.640  5602  5955 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-09 11:53:55.640  5602  5955 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-09 11:53:55.640  5602  5955 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-09 11:53:55.640  5602  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-09 11:53:59.914  5602  5648 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-09 11:53:59.916  5602  5956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: My test thread name). Connection data: Peer properties: [null null].
11-09 11:53:59.916  5602  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 11:53:59.918  5602  5956 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: My test thread name). Connection data: Peer properties: [null null].
11-09 11:53:59.918  5602  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 11:53:59.918  5602  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-09 11:53:59.918  5602  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 11:53:59.918  5602  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-09 11:53:59.918  5602  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-09 11:53:59.918  5602  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-09 11:53:59.918  5602  5956 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-09 11:53:59.918  5602  5956 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-09 11:53:59.919  5602  5956 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: My test thread name). Connection data: Peer properties: [null null].
11-09 11:53:59.919  5602  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-09 11:53:59.920  5602  5648 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-09 11:53:59.921  5602  5648 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-09 11:53:59.922  5602  5648 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-09 11:53:59.924  5602  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: My test thread name). Connection data: Peer properties: [null null].
11-09 11:53:59.924  5602  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-09 11:53:59.925  5602  5957 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 166, thread name: My test thread name): Test exception.
11-09 11:53:59.925  5602  5957 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 166, name: My test thread name). Connection data: Peer properties: [null null].
11-09 11:53:59.925  5602  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-09 11:53:59.925  5602  5957 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-09 11:53:59.926  5602  5957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: My test thread name). Connection data: Peer properties: [null null].
11-09 11:53:59.926  5602  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-09 11:53:59.927  5602  5648 E com.test.thalitest.ThaliTestRunner: testStart(io.jxcore.node.ConnectionHelperTest)
11-09 11:53:59.927  5602  5648 E com.test.thalitest.ThaliTestRunner: DiscoveryManager should be running
11-09 11:53:59.927  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-09 11:53:59.927  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: DiscoveryManager should be running
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testStart(ConnectionHelperTest.java:287)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at o,rg.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:59.928  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: testStop(io.jxcore.node.ConnectionHelperTest)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: DiscoveryManager should be running
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: DiscoveryManager should be running
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-09 11:53:59.929  5602  5648 E com.test.thalitest.Tha,liTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testStop(ConnectionHelperTest.java:315)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.929  5602  ,5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: 
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-09 11:53:59.929  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-09 11:53:59.930  5602  5648 E com.test.thalit,est.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.930 , 5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: testDispose(io.jxcore.node.ConnectionHelperTest)
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: DiscoveryManager should be running
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-09 11:53:59.930  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: DiscoveryManager should be running
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testDispose(ConnectionHelperTest.java:191)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(Fram,eworkMethod.java:50)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: testIsRunning(io.jxcore.node.ConnectionHelperTest)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: ConnectionManager state is different than NOT_STARTED
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is not <NOT_STARTED>
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was <NOT_STARTED>
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: ConnectionManager state is different than NOT_STARTED
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is not <NOT_STARTED>
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was <NOT_STARTED>
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testIsRunning(ConnectionHelperTest.java:413)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:59.931  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:53:59.932  5602  5648 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-09 11:53:59.934  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG UnitTest_app: 'Running unit tests'
11-09 11:53:59.934  5602  5648 I jxcore-log: 
11-09 11:53:59.934  5602  5648 I jxcore-log: *Native tests were executed*
11-09 11:53:59.934  5602  5648 I jxcore-log: 
11-09 11:53:59.934  5602  5648 I jxcore-log: Total number of executed tests:  82
11-09 11:53:59.934  5602  5648 I jxcore-log: 
11-09 11:53:59.934  5602  5648 I jxcore-log: Number of passed tests:  76
11-09 11:53:59.934  5602  5648 I jxcore-log: 
11-09 11:53:59.934  5602  5648 I jxcore-log: Number of failed tests:  6
11-09 11:53:59.934  5602  5648 I jxcore-log: 
11-09 11:53:59.934  5602  5648 I jxcore-log: Number of ignored tests:  0
11-09 11:53:59.934  5602  5648 I jxcore-log: 
11-09 11:53:59.934  5602  5648 I jxcore-log: Total duration:  54674
11-09 11:53:59.934  5602  5648 I jxcore-log: 
11-09 11:53:59.934  5602  5648 I jxcore-log: Failed to execute UT.
11-09 11:53:59.934  5602  5648 I jxcore-log: 
11-09 11:53:59.935  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-09 11:53:59.935  5602  5648 I jxcore-log: 
11-09 11:53:59.937  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-09 11:53:59.937  5602  5648 I jxcore-log: 
11-09 11:53:59.939  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.939  5602  5648 I jxcore-log: 
11-09 11:53:59.940  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.940  5602  5648 I jxcore-log: 
11-09 11:53:59.941  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.941  5602  5648 I jxcore-log: 
11-09 11:53:59.941  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.941  5602  5648 I jxcore-log: 
11-09 11:53:59.942  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.942  5602  5648 I jxcore-log: 
11-09 11:53:59.942  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.942  5602  5648 I jxcore-log: 
11-09 11:53:59.943  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-09 11:53:59.943  5602  5648 I jxcore-log: 
11-09 11:53:59.943  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-09 11:53:59.943  5602  5648 I jxcore-log: 
11-09 11:53:59.943  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.943  5602  5648 I jxcore-log: 
11-09 11:53:59.943  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.943  5602  5648 I jxcore-log: 
11-09 11:53:59.944  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 11:53:59.944  5602  5648 I jxcore-log: 
11-09 11:53:59.944  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.944  5602  5648 I jxcore-log: 
11-09 11:53:59.944  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 11:53:59.944  5602  5648 I jxcore-log: 
11-09 11:53:59.944  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.944  5602  5648 I jxcore-log: 
11-09 11:53:59.945  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 11:53:59.945  5602  5648 I jxcore-log: 
11-09 11:53:59.945  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.945  5602  5648 I jxcore-log: 
11-09 11:53:59.945  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.945  5602  5648 I jxcore-log: 
11-09 11:53:59.945  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.945  5602  5648 I jxcore-log: 
11-09 11:53:59.945  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.945  5602  5648 I jxcore-log: 
11-09 11:53:59.946  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.946  5602  5648 I jxcore-log: 
11-09 11:53:59.946  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.946  5602  5648 I jxcore-log: 
11-09 11:53:59.946  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.946  5602  5648 I jxcore-log: 
11-09 11:53:59.946  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.946  5602  5648 I jxcore-log: 
11-09 11:53:59.947  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.947  5602  5648 I jxcore-log: 
11-09 11:53:59.947  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.947  5602  5648 I jxcore-log: 
11-09 11:53:59.947  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.947  5602  5648 I jxcore-log: 
11-09 11:53:59.947  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.947  5602  5648 I jxcore-log: 
11-09 11:53:59.947  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.947  5602  5648 I jxcore-log: 
11-09 11:53:59.948  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-09 11:53:59.948  5602  5648 I jxcore-log: 
11-09 11:53:59.949  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.949  5602  5648 I jxcore-log: 
11-09 11:53:59.949  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.949  5602  5648 I jxcore-log: 
11-09 11:53:59.949  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.949  5602  5648 I jxcore-log: 
11-09 11:53:59.950  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.950  5602  5648 I jxcore-log: 
11-09 11:53:59.950  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.950  5602  5648 I jxcore-log: 
11-09 11:53:59.950  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.950  5602  5648 I jxcore-log: 
11-09 11:53:59.950  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.950  5602  5648 I jxcore-log: 
11-09 11:53:59.950  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.950  5602  5648 I jxcore-log: 
11-09 11:53:59.951  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.951  5602  5648 I jxcore-log: 
11-09 11:53:59.951  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.951  5602  5648 I jxcore-log: 
11-09 11:53:59.951  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.951  5602  5648 I jxcore-log: 
11-09 11:53:59.951  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.951  5602  5648 I jxcore-log: 
11-09 11:53:59.951  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-09 11:53:59.951  5602  5648 I jxcore-log: 
11-09 11:53:59.952  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.952  5602  5648 I jxcore-log: 
11-09 11:53:59.952  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.952  5602  5648 I jxcore-log: 
11-09 11:53:59.952  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.952  5602  5648 I jxcore-log: 
11-09 11:53:59.952  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.952  5602  5648 I jxcore-log: 
11-09 11:53:59.952  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.952  5602  5648 I jxcore-log: 
11-09 11:53:59.953  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.953  5602  5648 I jxcore-log: 
11-09 11:53:59.953  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.953  5602  5648 I jxcore-log: 
11-09 11:53:59.953  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.953  5602  5648 I jxcore-log: 
11-09 11:53:59.953  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.953  5602  5648 I jxcore-log: 
11-09 11:53:59.953  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.953  5602  5648 I jxcore-log: 
11-09 11:53:59.954  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.954  5602  5648 I jxcore-log: 
11-09 11:53:59.954  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.954  5602  5648 I jxcore-log: 
11-09 11:53:59.954  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 11:53:59.954  5602  5648 I jxcore-log: 
11-09 11:53:59.954  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.954  5602  5648 I jxcore-log: 
11-09 11:53:59.954  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 11:53:59.954  5602  5648 I jxcore-log: 
11-09 11:53:59.954  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.954  5602  5648 I jxcore-log: 
11-09 11:53:59.955  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-09 11:53:59.955  5602  5648 I jxcore-log: 
11-09 11:53:59.955  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 11:53:59.955  5602  5648 I jxcore-log: 
11-09 11:53:59.955  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.955  5602  5648 I jxcore-log: 
11-09 11:53:59.956  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.956  5602  5648 I jxcore-log: 
11-09 11:53:59.956  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.956  5602  5648 I jxcore-log: 
11-09 11:53:59.956  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.956  5602  5648 I jxcore-log: 
11-09 11:53:59.956  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.956  5602  5648 I jxcore-log: 
11-09 11:53:59.956  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.956  5602  5648 I jxcore-log: 
11-09 11:53:59.957  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.957  5602  5648 I jxcore-log: 
11-09 11:53:59.957  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 11:53:59.957  5602  5648 I jxcore-log: 
11-09 11:53:59.957  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.957  5602  5648 I jxcore-log: 
,11-09 11:53:59.957  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-09 11:53:59.957  5602  5648 I jxcore-log: 
11-09 11:53:59.957  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.957  5602  5648 I jxcore-log: 
11-09 11:53:59.958  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.958  5602  5648 I jxcore-log: 
11-09 11:53:59.958  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.958  5602  5648 I jxcore-log: 
11-09 11:53:59.958  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.958  5602  5648 I jxcore-log: 
11-09 11:53:59.958  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 11:53:59.958  5602  5648 I jxcore-log: 
11-09 11:53:59.958  5602  5602 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-09 11:53:59.958  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 11:53:59.958  5602  5648 I jxcore-log: 
11-09 11:53:59.958  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-09 11:53:59.958  5602  5648 I jxcore-log: 
11-09 11:53:59.959  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-09 11:53:59.959  5602  5648 I jxcore-log: 
11-09 11:53:59.959  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-09 11:53:59.959  5602  5648 I jxcore-log: 
11-09 11:53:59.964  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-09 11:53:59.964  5602  5648 I jxcore-log: 
11-09 11:53:59.964  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - WARN testUtils: 'myNameCallback not set!'
11-09 11:53:59.964  5602  5648 I jxcore-log: 
11-09 11:53:59.965  5602  5648 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
11-09 11:53:59.966  5602  5648 I jxcore-log: 2016-11-09 10:53:59 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-09 11:53:59.966  5602  5648 I jxcore-log: 
,11-09 11:54:01.926  5602  5648 I jxcore-log: 2016-11-09 10:54:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-09 11:54:01.926  5602  5648 I jxcore-log: 
,11-09 11:54:02.248  5602  5648 I jxcore-log: 2016-11-09 10:54:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-09 11:54:02.248  5602  5648 I jxcore-log: 
,11-09 11:54:02.262  5602  5648 I jxcore-log: 2016-11-09 10:54:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-09 11:54:02.262  5602  5648 I jxcore-log: 
,11-09 11:54:03.333  5602  5648 I jxcore-log: 2016-11-09 10:54:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-09 11:54:03.333  5602  5648 I jxcore-log: 
,11-09 11:54:03.500  5602  5648 I jxcore-log: 2016-11-09 10:54:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-09 11:54:03.500  5602  5648 I jxcore-log: 
,11-09 11:54:03.505  5602  5648 I jxcore-log: 2016-11-09 10:54:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-09 11:54:03.505  5602  5648 I jxcore-log: 
,11-09 11:54:03.510  5602  5648 I jxcore-log: 2016-11-09 10:54:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-09 11:54:03.510  5602  5648 I jxcore-log: 
,11-09 11:54:03.544   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:54:03.987  5602  5648 I jxcore-log: 2016-11-09 10:54:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-09 11:54:03.987  5602  5648 I jxcore-log: 
,11-09 11:54:04.030  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-09 11:54:04.030  5602  5648 I jxcore-log: 
,11-09 11:54:04.043  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-09 11:54:04.043  5602  5648 I jxcore-log: 
,11-09 11:54:04.047  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-09 11:54:04.047  5602  5648 I jxcore-log: 
,11-09 11:54:04.331  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-09 11:54:04.331  5602  5648 I jxcore-log: 
,11-09 11:54:04.468  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-09 11:54:04.468  5602  5648 I jxcore-log: 
,11-09 11:54:04.545   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:54:04.838  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-09 11:54:04.838  5602  5648 I jxcore-log: 
,11-09 11:54:04.872  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-09 11:54:04.872  5602  5648 I jxcore-log: 
,11-09 11:54:04.878  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-09 11:54:04.878  5602  5648 I jxcore-log: 
,11-09 11:54:04.883  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-09 11:54:04.883  5602  5648 I jxcore-log: 
,11-09 11:54:04.891  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-09 11:54:04.891  5602  5648 I jxcore-log: 
,11-09 11:54:04.903  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-09 11:54:04.903  5602  5648 I jxcore-log: 
,11-09 11:54:04.908  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-09 11:54:04.908  5602  5648 I jxcore-log: 
,11-09 11:54:04.934  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-09 11:54:04.934  5602  5648 I jxcore-log: 
,11-09 11:54:04.971  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-09 11:54:04.971  5602  5648 I jxcore-log: 
,11-09 11:54:04.978  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-09 11:54:04.978  5602  5648 I jxcore-log: 
,11-09 11:54:04.984  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-09 11:54:04.984  5602  5648 I jxcore-log: 
,11-09 11:54:04.999  5602  5648 I jxcore-log: 2016-11-09 10:54:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-09 11:54:04.999  5602  5648 I jxcore-log: 
,11-09 11:54:05.004  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-09 11:54:05.004  5602  5648 I jxcore-log: 
,11-09 11:54:05.010  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-09 11:54:05.010  5602  5648 I jxcore-log: 
,11-09 11:54:05.015  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-09 11:54:05.015  5602  5648 I jxcore-log: 
,11-09 11:54:05.027  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-09 11:54:05.027  5602  5648 I jxcore-log: 
,11-09 11:54:05.035  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-09 11:54:05.035  5602  5648 I jxcore-log: 
,11-09 11:54:05.056  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-09 11:54:05.056  5602  5648 I jxcore-log: 
,11-09 11:54:05.067  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-09 11:54:05.067  5602  5648 I jxcore-log: 
,11-09 11:54:05.079  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-09 11:54:05.079  5602  5648 I jxcore-log: 
,11-09 11:54:05.089  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-09 11:54:05.089  5602  5648 I jxcore-log: 
,11-09 11:54:05.102  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-09 11:54:05.102  5602  5648 I jxcore-log: 
,11-09 11:54:05.112  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-09 11:54:05.112  5602  5648 I jxcore-log: 
,11-09 11:54:05.118  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-09 11:54:05.118  5602  5648 I jxcore-log: 
,11-09 11:54:05.124  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-09 11:54:05.124  5602  5648 I jxcore-log: 
,11-09 11:54:05.130  5602  5648 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-09 11:54:05.131  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - INFO testUtils: 'BLE multiple advertisement supported'
11-09 11:54:05.131  5602  5648 I jxcore-log: 
,11-09 11:54:05.288  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:05.288  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:05.288  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:05.288  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:05.288  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:05.288  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:05.288  5602  5648 I jxcore-log: 
,11-09 11:54:05.461  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:05.461  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:05.461  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:05.461  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:05.461  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:05.461  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:05.461  5602  5648 I jxcore-log: 
,11-09 11:54:05.464  5602  5648 I jxcore-log: 2016-11-09 10:54:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:05.464  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:05.464  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:05.464  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:05.464  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:05.464  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:05.464  5602  5648 I jxcore-log: 
,11-09 11:54:05.546   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:54:06.007  5602  5648 I jxcore-log: 2016-11-09 10:54:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:06.007  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:06.007  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:06.007  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:06.007  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:06.007  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:06.007  5602  5648 I jxcore-log: 
,11-09 11:54:06.010  5602  5648 I jxcore-log: 2016-11-09 10:54:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:06.010  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:06.010  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:06.010  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:06.010  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:06.010  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:06.010  5602  5648 I jxcore-log: 
,11-09 11:54:06.547   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:54:06.978  5602  5648 I jxcore-log: 2016-11-09 10:54:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:06.978  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:06.978  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:06.978  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:06.978  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:06.978  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:06.978  5602  5648 I jxcore-log: 
,11-09 11:54:06.981  5602  5648 I jxcore-log: 2016-11-09 10:54:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:06.981  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:06.981  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:06.981  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:06.981  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:06.981  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:06.981  5602  5648 I jxcore-log: 
,11-09 11:54:07.548   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 11:54:08.018  5602  5648 I jxcore-log: 2016-11-09 10:54:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:08.018  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:08.018  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:08.018  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:08.018  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:08.018  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:08.018  5602  5648 I jxcore-log: 
,11-09 11:54:08.022  5602  5648 I jxcore-log: 2016-11-09 10:54:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:08.022  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:08.022  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:08.022  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:08.022  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:08.022  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:08.022  5602  5648 I jxcore-log: 
,11-09 11:54:08.548   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-09 11:54:08.567  5098  5098 W Binder_9: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33134]" dev="sockfs" ino=33134 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:54:08.571  5098  5098 W Binder_9: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33134]" dev="sockfs" ino=33134 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:54:08.564   926   947 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
11-09 11:54:08.576  3635  3635 I Keyboard.Facilitator: onFinishInput()
,11-09 11:54:08.590   926   947 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-09 11:54:08.590   926   947 I Adreno  : Build Date                       : 12/06/15
11-09 11:54:08.590   926   947 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-09 11:54:08.590   926   947 I Adreno  : Local Branch                     : mybranch17112971
11-09 11:54:08.590   926   947 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-09 11:54:08.590   926   947 I Adreno  : Remote Branch                    : NONE
11-09 11:54:08.590   926   947 I Adreno  : Reconstruct Branch               : NOTHING
,11-09 11:54:08.618   384  2942 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (231 us)
,11-09 11:54:09.062  5602  5648 I jxcore-log: 2016-11-09 10:54:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:09.062  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:09.062  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:09.062  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:09.062  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:09.062  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:09.062  5602  5648 I jxcore-log: 
,11-09 11:54:09.066  5602  5648 I jxcore-log: 2016-11-09 10:54:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:09.066  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:09.066  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:09.066  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:09.066  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:09.066  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:09.066  5602  5648 I jxcore-log: 
,11-09 11:54:09.280  5602  5602 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-09 11:54:09.280  5602  5602 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-09 11:54:09.311   926   947 I sensors : batch
,11-09 11:54:09.312   926   947 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-09 11:54:09.315   926   947 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,11-09 11:54:09.317   926   947 I sensors : activate
,11-09 11:54:09.316  5602  5602 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@cd4ad63 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@5e5eeff, 16908290=android.view.AbsSavedState$1@5e5eeff}, android:focusedViewId=100}]}]
11-09 11:54:09.317  5602  5602 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-09 11:54:09.318  5602  5602 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-09 11:54:09.318  5602  5602 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-09 11:54:09.319   926   945 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,11-09 11:54:09.319   384   384 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f9d9c3c00
11-09 11:54:09.319   384   384 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-09 11:54:09.324   926  2632 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-09 11:54:09.325   926  2632 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-09 11:54:09.620   384   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-09 11:54:09.623   384   384 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
11-09 11:54:09.628   926  3022 D SurfaceControl: Excessive delay in setPowerMode(): 309ms
,11-09 11:54:09.638   926   947 I DreamManagerService: Entering dreamland.
,11-09 11:54:09.638   926   947 I PowerManagerService: Dozing...
,11-09 11:54:09.639   926   941 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-09 11:54:09.664  5098  5098 W Binder_9: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34553]" dev="sockfs" ino=34553 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:54:09.664  5098  5098 W Binder_9: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34553]" dev="sockfs" ino=34553 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-09 11:54:09.671   926  3367 I sensors : batch
11-09 11:54:09.671   926  3367 I sensors : activate
,11-09 11:54:09.675   926  2632 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-09 11:54:09.675   926  2632 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-09 11:54:09.684   512  2976 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-09 11:54:09.704   926  2950 E native  : do suspend false
,11-09 11:54:09.712  3754  4673 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-09 11:54:09.713  3754  4673 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-09 11:54:09.713  3754  4673 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-09 11:54:09.713   525  1410 D         : oem-qmi: Connection accepted
11-09 11:54:09.714   525  1410 D         : oem-qmi: Waiting to accept connection
,11-09 11:54:09.715   926   926 I sensors : activate
,11-09 11:54:09.716   512  2974 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-09 11:54:09.718   926  2950 D WifiConfigStore: No blacklist allowed without epno enabled
,11-09 11:54:09.718   926  2632 I hubconnection: sensorhub said: 'activate 31 enable:0'
11-09 11:54:09.719  3754  4673 D         : oem_qmi_lib:output 0
11-09 11:54:09.720  3754  4673 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-09 11:54:09.728   926  2950 E native  : do suspend true
,11-09 11:54:09.746  3754  4673 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
11-09 11:54:09.746  3754  4673 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
,11-09 11:54:09.746  3754  4673 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-09 11:54:09.747   525  1410 D         : oem-qmi: Connection accepted
11-09 11:54:09.747   525  1410 D         : oem-qmi: Waiting to accept connection
,11-09 11:54:09.752  3754  4673 D         : oem_qmi_lib:output 0
,11-09 11:54:09.752  3754  4673 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-09 11:54:10.096  5602  5648 I jxcore-log: 2016-11-09 10:54:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13,
11-09 11:54:10.096  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:10.096  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:10.096  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:10.096  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:10.096  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:10.096  5602  5648 I jxcore-log: 
11-09 11:54:10.101  5602  5648 I jxcore-log: 2016-11-09 10:54:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:10.101  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:10.101  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:10.101  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:10.101  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:10.101  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:10.101  5602  5648 I jxcore-log: 
,11-09 11:54:10.194   926  2950 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,11-09 11:54:11.131  5602  5648 I jxcore-log: 2016-11-09 10:54:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:11.131  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:11.131  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:11.131  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:11.131  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:11.131  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:11.131  5602  5648 I jxcore-log: 
,11-09 11:54:11.136  5602  5648 I jxcore-log: 2016-11-09 10:54:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:11.136  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:11.136  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:11.136  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:11.136  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:11.136  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:11.136  5602  5648 I jxcore-log: 
,11-09 11:54:12.173  5602  5648 I jxcore-log: 2016-11-09 10:54:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:12.173  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:12.173  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:12.173  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:12.173  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:12.173  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:12.173  5602  5648 I jxcore-log: 
,11-09 11:54:12.177  5602  5648 I jxcore-log: 2016-11-09 10:54:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:12.177  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:12.177  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:12.177  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:12.177  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:12.177  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:12.177  5602  5648 I jxcore-log: 
,11-09 11:54:13.209  5602  5648 I jxcore-log: 2016-11-09 10:54:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:13.209  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:13.209  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:13.209  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:13.209  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:13.209  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:13.209  5602  5648 I jxcore-log: 
,11-09 11:54:13.215  5602  5648 I jxcore-log: 2016-11-09 10:54:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:13.215  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:13.215  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:13.215  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:13.215  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:13.215  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:13.215  5602  5648 I jxcore-log: 
,11-09 11:54:13.535  4063  4481 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-09 11:54:14.292  5602  5648 I jxcore-log: 2016-11-09 10:54:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:14.292  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:14.292  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:14.292  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:14.292  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:14.292  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:14.292  5602  5648 I jxcore-log: 
,11-09 11:54:14.298  5602  5648 I jxcore-log: 2016-11-09 10:54:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:14.298  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:14.298  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:14.298  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:14.298  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:14.298  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:14.298  5602  5648 I jxcore-log: 
,11-09 11:54:14.402   926  2950 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,11-09 11:54:15.332  5602  5648 I jxcore-log: 2016-11-09 10:54:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:15.332  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:15.332  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:15.332  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:15.332  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:15.332  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:15.332  5602  5648 I jxcore-log: 
,11-09 11:54:15.340  5602  5648 I jxcore-log: 2016-11-09 10:54:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:15.340  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:15.340  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:15.340  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:15.340  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:15.340  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:15.340  5602  5648 I jxcore-log: 
,11-09 11:54:15.825   926  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-09 11:54:16.375  5602  5648 I jxcore-log: 2016-11-09 10:54:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:16.375  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:16.375  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:16.375  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:16.375  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:16.375  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:16.375  5602  5648 I jxcore-log: 
,11-09 11:54:16.381  5602  5648 I jxcore-log: 2016-11-09 10:54:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:16.381  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:16.381  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:16.381  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:16.381  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:16.381  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:16.381  5602  5648 I jxcore-log: 
,11-09 11:54:17.412  5602  5648 I jxcore-log: 2016-11-09 10:54:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:17.412  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:17.412  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:17.412  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:17.412  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:17.412  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:17.412  5602  5648 I jxcore-log: 
,11-09 11:54:17.419  5602  5648 I jxcore-log: 2016-11-09 10:54:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:17.419  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:17.419  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:17.419  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:17.419  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:17.419  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:17.419  5602  5648 I jxcore-log: 
,11-09 11:54:18.468  5602  5648 I jxcore-log: 2016-11-09 10:54:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:18.468  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:18.468  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:18.468  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:18.468  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:18.468  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:18.468  5602  5648 I jxcore-log: 
,11-09 11:54:18.472  5602  5648 I jxcore-log: 2016-11-09 10:54:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:18.472  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:18.472  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:18.472  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:18.472  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:18.472  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:18.472  5602  5648 I jxcore-log: 
,11-09 11:54:19.502  5602  5648 I jxcore-log: 2016-11-09 10:54:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 11:54:19.502  5602  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 11:54:19.502  5602  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 11:54:19.502  5602  5648 I jxcore-log: emit@events.js:82:1
11-09 11:54:19.502  5602  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 11:54:19.502  5602  5648 I jxcore-log: emit@events.js:82:1'
11-09 11:54:19.502  5602  5648 I jxcore-log: 
,11-09 11:54:19.513  5602  5648 E jxcore  : Error!: error is undefined
11-09 11:54:19.513  5602  5648 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-09 11:54:19.518  5602  5648 I jxcore-log: 2016-11-09 10:54:19 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-09 11:54:19.518  5602  5648 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-09 11:54:19.518  5602  5648 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-09 11:54:19.518  5602  5648 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-09 11:54:19.518  5602  5648 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-09 11:54:19.518  5602  5648 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-09 11:54:19.518  5602  5648 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-09 11:54:19.518  5602  5648 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-09 11:54:19.520  5602  5648 I jxcore-log: 2016-11-09 10:54:19 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-09 11:54:19.520  5602  5648 I jxcore-log: 
11-09 11:54:19.522  5602  5648 E jxcore-log: TypeError: 
11-09 11:54:19.522  5602  5648 E jxcore-log: error is undefined
11-09 11:54:19.522  5602  5648 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-09 11:54:19.522  5602  5648 E jxcore-log: 
,11-09 11:54:19.612   926  3368 I WindowState: WIN DEATH: Window{541854b u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-09 11:54:19.612   926  3090 D GraphicsStats: Buffer count: 2
11-09 11:54:19.613   926  2952 D WifiService: Client connection lost with reason: 4
,11-09 11:54:19.613  5823  5876 D BtGatt.GattService: Binder is dead - unregistering client (5)!
11-09 11:54:19.614  5823  5842 D BtGatt.AdvertiseManager: message : 1
,11-09 11:54:19.616  5823  5842 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-09 11:54:19.617  5823  5842 D BtGatt.AdvertiseManager: app died - unregistering client : 5
11-09 11:54:19.618  5823  5842 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-09 11:54:19.625   527   527 I Zygote  : Process 5602 exited cleanly (139)
,11-09 11:54:19.629   926  3092 I ActivityManager: Process com.test.thalitest (pid 5602) has died
,11-09 11:54:19.645   926  3092 I ActivityManager: Start proc 5967:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-09 11:54:19.647  5823  5839 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=255, status=0
11-09 11:54:19.647  5823  5839 E BtGatt.ContextMap: Context not found for ID 255
,11-09 11:54:19.718  5967  5967 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-09 11:54:19.737  5967  5967 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-09 11:54:19.743  5967  5967 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 447-449)
,11-09 11:54:19.743  5967  5967 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-09 11:54:19.753  5967  5967 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22cc75c}
,11-09 11:54:19.753  5967  5967 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-09 11:54:19.754  5967  5967 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-09 11:54:19.757  5967  5967 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-09 11:54:19.758  5967  5967 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-09 11:54:19.769  5967  5967 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-09 11:54:19.776  5967  5967 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-09 11:54:19.777  5967  5967 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-09 11:54:19.777  5967  5967 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-09 11:54:19.777  5967  5967 I Adreno  : Build Date                       : 12/06/15
11-09 11:54:19.777  5967  5967 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-09 11:54:19.777  5967  5967 I Adreno  : Local Branch                     : mybranch17112971
11-09 11:54:19.777  5967  5967 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-09 11:54:19.777  5967  5967 I Adreno  : Remote Branch                    : NONE
11-09 11:54:19.777  5967  5967 I Adreno  : Reconstruct Branch               : NOTHING
,11-09 11:54:19.808   926   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e34f560:true
,11-09 11:54:19.817   408   408 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[28349]" dev="sockfs" ino=28349 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-09 11:54:19.817   408   408 W Binder_2: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[28349]" dev="sockfs" ino=28349 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 11:54:19.833  5967  5967 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-09 11:54:19.840  5967  5967 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-09 11:54:19.861   408   408 W Binder_2: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[34603]" dev="sockfs" ino=34603 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 11:54:19.861   408   408 W Binder_2: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[34603]" dev="sockfs" ino=34603 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-09 11:54:19.867  5967  6003 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-09 11:54:19.864  3784  3784 W Binder_7: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[28361]" dev="sockfs" ino=28361 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-09 11:54:19.864  3784  3784 W Binder_7: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[28361]" dev="sockfs" ino=28361 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-09 11:54:19.871  5967  5990 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-09 11:54:19.902  5967  6003 I OpenGLRenderer: Initialized EGL, version 1.4
,11-09 11:54:19.914  3784  3784 W Binder_7: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[36006]" dev="sockfs" ino=36006 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:54:19.914  3784  3784 W Binder_7: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[36006]" dev="sockfs" ino=36006 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:54:19.914  3368  3368 W Binder_6: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[36005]" dev="sockfs" ino=36005 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:54:19.914  3368  3368 W Binder_6: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[36005]" dev="sockfs" ino=36005 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:54:19.917   926  3784 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5602 uid 10077
,11-09 11:54:19.923  3635  3635 I Keyboard.Facilitator: onFinishInput()
,11-09 11:54:19.941   926   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +275ms (total +310ms)
,11-09 11:54:19.942  5967  5967 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5967
,11-09 11:54:19.991  5965  5965 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-09 11:54:20.001  5967  5967 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-09 11:54:20.006  5965  5965 D AndroidRuntime: CheckJNI is OFF
,11-09 11:54:20.030  5965  5965 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-09 11:54:20.061  5965  5965 I Radio-JNI: register_android_hardware_Radio DONE
,11-09 11:54:20.075  5965  5965 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-09 11:54:20.082   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-09 11:54:20.082   926   939 I ActivityManager: Killing 5967:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-09 11:54:20.115   926  3092 D GraphicsStats: Buffer count: 2
,11-09 11:54:20.115   926  3784 I WindowState: WIN DEATH: Window{7d9bbaf u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-09 11:54:20.190   926   939 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-09 11:54:20.191   926   939 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-09 11:54:20.192   926   951 I art     : Starting a blocking GC Explicit
,11-09 11:54:20.193   926   939 E ActivityManager: Failure starting process com.test.thalitest
11-09 11:54:20.193   926   939 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-09 11:54:20.193   926   939 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:54:20.193   926   939 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:54:20.193   926   939 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-09 11:54:20.193   926   939 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-09 11:54:20.194   926   939 I ActivityManager:   Force finishing activity ActivityRecord{e2ab3b0 u0 com.test.thalitest/.MainActivity t68}
,11-09 11:54:20.203   926  3092 W ActivityManager: Spurious death for ProcessRecord{9cf5745 0:com.test.thalitest/u0a77}, curProc for 5967: null
,11-09 11:54:20.279   926   951 I art     : Explicit concurrent mark sweep GC freed 16863(1145KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 1.683ms total 86.345ms
,11-09 11:54:20.298   926   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-09 11:54:20.302  5965  5965 I art     : System.exit called, status: 0
11-09 11:54:20.302  5965  5965 I AndroidRuntime: VM exiting with result code 0.
,11-09 11:54:20.318   926   951 I ActivityManager: Start proc 6017:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-09 11:54:20.318   926   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-09 11:54:20.323   926   939 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-09 11:54:20.327  5823  5823 D BluetoothMapAppObserver: onReceive
,11-09 11:54:20.328  5823  5823 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-09 11:54:20.336   926  2937 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-09 11:54:20.339  3635  3635 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-09 11:54:20.339  4063  4133 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-09 11:54:20.357  3635  6029 I Keyboard.Facilitator.DecoderInitializer: run()
,11-09 11:54:20.360  3350  6031 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
11-09 11:54:20.364  3635  6029 I Decoder : createOrResetDecoder
,11-09 11:54:20.387  3754  3754 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-09 11:54:20.413  3529  3529 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-09 11:54:20.413  3529  3529 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-09 11:54:20.426   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-09 11:54:20.424  5496  5496 W Binder_A: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[28828]" dev="sockfs" ino=28828 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:54:20.429   926  5496 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5967 uid 10077
11-09 11:54:20.430  3635  3635 I Keyboard.Facilitator: onFinishInput()
11-09 11:54:20.424  5496  5496 W Binder_A: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[28828]" dev="sockfs" ino=28828 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 11:54:20.481    28    28 W kworker/2:1: type=1400 audit(0.0:139): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-09 11:54:20.491  3529  3529 I ConfigService: onCreate
,11-09 11:54:20.492  3922  6037 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-09 11:54:20.492  3922  6037 D AccountUtils: Clearing selected account for com.test.thalitest
11-09 11:54:20.487    28    28 W kworker/2:1: type=1400 audit(0.0:140): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-09 11:54:20.501    28    28 W kworker/2:1: type=1400 audit(0.0:141): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-09 11:54:20.512  3529  3529 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/ns.db'.
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:54:20.512  3529  3529 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 11:54:20.513  3529  3529 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-09 11:54:20.515  3529  3529 E AndroidRuntime: FATAL EXCEPTION: main
11-09 11:54:20.515  3529  3529 E AndroidRuntime: Process: com.google.process.gapps, PID: 3529
11-09 11:54:20.515  3529  3529 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-09 11:54:20.51,5  3529  3529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 11:54:20.515  3529  3529 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 11:54:20.518  3635  6029 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-09 11:54:20.518   926  6040 E DropBoxManagerService: Can't write: system_app_crash
11-09 11:54:20.518   926  6040 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-09 11:54:20.518   926  6040 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-09 11:54:20.518   926  6040 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-09 11:54:20.518   926  6040 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-09 11:54:20.518   926  6040 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-09 11:54:20.518   926  6040 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-09 11:54:20.518   926  6040 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-09 11:54:20.518   926  6040 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-09 11:54:20.518   926  6040 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-09 11:54:20.518   926  6040 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-09 11:54:20.518   926  6040 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-09 11:54:20.518   926  6040 E DropBoxManagerService: 	... 5 more
11-09 11:54:20.519  3529  3529 I Process : Sending signal. PID: 3529 SIG: 9
11-09 11:54:20.542   926  2952 D WifiService: Client connection lost with reason: 4
11-09 11:54:20.543   926   936 I ActivityManager: Process com.google.process.gapps (pid 3529) has died
11-09 11:54:20.543   926   936 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
11-09 11:54:20.544   926   936 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
11-09 11:54:20.544   926   936 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 20999ms
11-09 11:54:20.544   926   936 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,11-09 11:54:20.546  3635  3635 W GmsClient: service died
11-09 11:54:20.552  3922  6037 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-09 11:54:20.565  3350  6031 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
11-09 11:54:20.566  3350  6031 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-09 11:54:20.566  3350  6031 E AndroidRuntime: Process: android.process.acore, PID: 3350
11-09 11:54:20.566  3350  6031 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:54:20.566  3350  6031 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-09 11:54:20.570   926  3092 I ActivityManager: Start proc 6042:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
11-09 11:54:20.576   926  6048 E DropBoxManagerService: Can't write: system_app_crash
11-09 11:54:20.576   926  6048 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-09 11:54:20.576   926  6048 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-09 11:54:20.576   926  6048 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-09 11:54:20.576   926  6048 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-09 11:54:20.576   926  6048 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-09 11:54:20.576   926  6048 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-09 11:54:20.576   926  6048 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-09 11:54:20.576   926  6048 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-09 11:54:20.576   926  6048 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-09 11:54:20.576   926  6048 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-09 11:54:20.576   926  6048 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-09 11:54:20.576   926  6048 E DropBoxManagerService: 	... 5 more
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:54:20.579  3922  6037 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-09 11:54:20.579  3922  6037 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-09 11:54:20.588  3350  6031 I Process : Sending signal. PID: 3350 SIG: 9

```
