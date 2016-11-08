#### Test 927335313b70e13_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-08 11:41:47.821  4013  4277 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
11-08 11:41:47.897  4013  4277 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,11-08 11:41:48.352  5636  5636 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-08 11:41:48.357  5636  5636 D AndroidRuntime: CheckJNI is OFF
11-08 11:41:48.386  5636  5636 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-08 11:41:48.420  5636  5636 I Radio-JNI: register_android_hardware_Radio DONE
11-08 11:41:48.436  5636  5636 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-08 11:41:48.449   929  3182 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-08 11:41:48.466  5636  5636 D AndroidRuntime: Shutting down VM
11-08 11:41:48.483  3994  5632 W SearchService: Abort, client detached.
11-08 11:41:48.488  3994  3994 I HotwordDetector: Closing mic
11-08 11:41:48.489  3994  4247 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@918f873
11-08 11:41:48.491  3994  4264 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-08 11:41:48.509   929  3450 I ActivityManager: Start proc 5645:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-08 11:41:48.567   514  4269 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-08 11:41:48.568   514  4269 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-08 11:41:48.574   514  4269 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-08 11:41:48.574   514  4269 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-08 11:41:48.575   514  3035 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-08 11:41:48.577  3994  4261 I MicroRecognitionRnrImpl: Detection finished
11-08 11:41:48.577  3994  4252 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-08 11:41:48.612  5645  5645 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-08 11:41:48.646  5645  5645 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-08 11:41:48.705  5645  5645 I LibraryLoader: Time to load native libraries: 56 ms (timestamps 6194-6250)
,11-08 11:41:48.706  5645  5645 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 11:41:48.738  5645  5645 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c1dcb8a}
11-08 11:41:48.738  5645  5645 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-08 11:41:48.739  5645  5645 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-08 11:41:48.744  5645  5645 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-08 11:41:48.746  5645  5645 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-08 11:41:48.793  5645  5645 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-08 11:41:48.811  5645  5645 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-08 11:41:48.811  5645  5645 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 11:41:48.811  5645  5645 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 11:41:48.811  5645  5645 I Adreno  : Build Date                       : 12/06/15
11-08 11:41:48.811  5645  5645 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 11:41:48.811  5645  5645 I Adreno  : Local Branch                     : mybranch17112971
11-08 11:41:48.811  5645  5645 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 11:41:48.811  5645  5645 I Adreno  : Remote Branch                    : NONE
11-08 11:41:48.811  5645  5645 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 11:41:48.867   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@736ae79:true
,11-08 11:41:48.903   404   404 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[24180]" dev="sockfs" ino=24180 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:41:48.903   404   404 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[24180]" dev="sockfs" ino=24180 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:41:48.917  5645  5645 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-08 11:41:48.927  5645  5645 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-08 11:41:48.956  2302  2302 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32888]" dev="sockfs" ino=32888 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:41:48.956  2302  2302 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32888]" dev="sockfs" ino=32888 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-08 11:41:48.960  5645  5682 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-08 11:41:48.960  3877  3877 W Binder_A: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[15085]" dev="sockfs" ino=15085 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:41:48.965  5645  5669 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-08 11:41:48.960  3877  3877 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15085]" dev="sockfs" ino=15085 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:41:48.994  5645  5682 I OpenGLRenderer: Initialized EGL, version 1.4
,11-08 11:41:49.073  3449  3449 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32891]" dev="sockfs" ino=32891 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:41:49.073  3449  3449 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32891]" dev="sockfs" ino=32891 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:41:49.079   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +588ms
,11-08 11:41:49.076  3877  3877 W Binder_A: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32890]" dev="sockfs" ino=32890 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:41:49.076  3877  3877 W Binder_A: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32890]" dev="sockfs" ino=32890 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:41:49.080  3686  3686 I Keyboard.Facilitator: onFinishInput()
,11-08 11:41:49.111  5645  5645 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5645
,11-08 11:41:49.218  5645  5645 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-08 11:41:49.420  5645  5685 D jxcore_app_log: JniHelper::setJavaVM(0xf507c000), pthread_self() = -583268048
,11-08 11:41:49.424  5645  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-08 11:41:49.424  5645  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-08 11:41:49.424  5645  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-08 11:41:49.424  5645  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-08 11:41:49.424  5645  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-08 11:41:49.425  5645  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f1b269 added. We now have 1 listener(s)
,11-08 11:41:49.431  5645  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-08 11:41:49.432  5645  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 11:41:49.432  5645  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-08 11:41:49.434  5645  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-08 11:41:49.436  5645  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@731681c added. We now have 1 listener(s)
11-08 11:41:49.436  5645  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-08 11:41:49.441   929  2986 D WifiService: New client listening to asynchronous messages
,11-08 11:41:49.442  5645  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-08 11:41:49.442  5645  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-08 11:41:49.442  5645  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-08 11:41:49.442  5645  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-08 11:41:49.442  5645  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-08 11:41:49.444  5645  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:41:49.444  5645  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-08 11:41:49.448  5645  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-08 11:41:49.448  5645  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:41:49.448  5645  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:41:49.448  5645  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:41:49.448  5645  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:41:49.448  5645  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:41:49.448  5645  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:41:49.448  5645  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:41:49.448  5645  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 11:41:49.448  5645  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-08 11:41:49.448  5645  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
11-08 11:41:49.448  5645  5685 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-08 11:41:49.557  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:41:49.561  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:41:49.564  5645  5645 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-08 11:41:49.847  5645  5692 W jxcore-log: Initializing JXcore engine
11-08 11:41:49.848  5645  5692 W jxcore-log: JXcore engine is ready
,11-08 11:41:49.870  5692  5692 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12595 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-08 11:41:49.870  5692  5692 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15479]" dev="sockfs" ino=15479 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-08 11:41:49.870  5692  5692 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-08 11:41:49.870  5692  5692 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32196]" dev="sockfs" ino=32196 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-08 11:41:49.879  5645  5692 W jxcore-log: Starting JXcore engine
,11-08 11:41:49.929  5645  5692 W jxcore-log: Platform android
11-08 11:41:49.929  5645  5692 W jxcore-log: 
,11-08 11:41:49.929  5645  5692 W jxcore-log: Process ARCH arm
11-08 11:41:49.929  5645  5692 W jxcore-log: 
,11-08 11:41:50.073  5645  5692 I jxcore-log: JXcore Cordova bridge is ready!
11-08 11:41:50.073  5645  5692 I jxcore-log: 
,11-08 11:41:50.073  5645  5692 W jxcore-log: JXcore engine is started
,11-08 11:41:50.082  5645  5685 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-08 11:41:50.088  5645  5645 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-08 11:41:51.955  3595  3595 I ConfigService: onDestroy
,11-08 11:41:53.496   929   940 I ActivityManager: Killing 5070:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-08 11:41:54.883   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-08 11:41:57.624   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:41:58.625   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:41:59.627   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:41:59.800  5645  5692 I jxcore-log: 2016-11-08 10:41:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-08 11:41:59.800  5645  5692 I jxcore-log: 
,11-08 11:41:59.802  5645  5692 I jxcore-log: 2016-11-08 10:41:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-08 11:41:59.802  5645  5692 I jxcore-log: 
,11-08 11:41:59.806  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:41:59.806  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:41:59.806  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:41:59.806  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:41:59.806  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:41:59.806  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:41:59.806  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:41:59.806  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 11:41:59.808  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 11:41:59.809  5645  5692 I jxcore-log: 2016-11-08 10:41:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-08 11:41:59.809  5645  5692 I jxcore-log: 
11-08 11:41:59.811  5645  5692 I jxcore-log: 2016-11-08 10:41:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-08 11:41:59.811  5645  5692 I jxcore-log: 
,11-08 11:42:00.005   929   929 I ActivityManager: Killing 5435:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-08 11:42:00.059  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-08 11:42:00.059  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34fe4e5 added. We now have 2 listener(s)
11-08 11:42:00.060  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:42:00.060  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 11:42:00.060  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 11:42:00.060  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 11:42:00.060  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee06bba added. We now have 2 listener(s)
11-08 11:42:00.060  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-08 11:42:00.060  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 11:42:00.062  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:42:00.067  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:42:00.067  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:00.067  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:00.067  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:00.067  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:00.067  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:42:00.067  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:42:00.067  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 11:42:00.070  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 11:42:00.070  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
11-08 11:42:00.071  5645  5692 D ExecuteNativeTests: Running unit tests
,11-08 11:42:00.072  5645  5692 D BluetoothAdapter: enable(): BT is already enabled..!
11-08 11:42:00.072   929  3449 D WifiService: setWifiEnabled: true pid=5645, uid=10077
11-08 11:42:00.072   929  3449 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:42:00.073  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:00.077  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:00.628   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:01.570  3994  5694 W CronetSyncConnectionRcs: Upload content type not set.
,11-08 11:42:01.629   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:01.685  4912  4959 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-08 11:42:01.695  4912  4912 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-08 11:42:02.630   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-08 11:42:10.081  5645  5692 I com.test.thalitest.ThaliTestRunner: Running UT
,11-08 11:42:10.159  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-08 11:42:10.159  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@acec83c added. We now have 3 listener(s)
11-08 11:42:10.160  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 11:42:10.160  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-08 11:42:10.160  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 11:42:10.160  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 11:42:10.160  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@575b9c5 added. We now have 3 listener(s)
11-08 11:42:10.160  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 11:42:10.161  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-08 11:42:10.163  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:42:10.165  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:42:10.165  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:10.165  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:10.165  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:10.165  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:10.165  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:42:10.165  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:42:10.165  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 11:42:10.166  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 11:42:10.166  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 11:42:10.173  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-08 11:42:10.173  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 11:42:10.173  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:42:10.173  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:42:10.173  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-08 11:42:10.173  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:10.174  5645  5692 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-08 11:42:10.174  5645  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-08 11:42:10.174  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-08 11:42:10.174  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:42:10.174  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:42:10.174  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:42:10.175  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-08 11:42:10.175  5645  5692 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-08 11:42:10.177  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-08 11:42:10.179  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-08 11:42:10.179  5645  5692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 11:42:10.179  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:10.180  5645  5692 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 11:42:10.180  5645  5692 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,11-08 11:42:10.180  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-08 11:42:10.180  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:42:10.180  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 11:42:10.180  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 11:42:10.180  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:42:10.181  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 11:42:10.183  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-08 11:42:10.184  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-08 11:42:10.184  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 11:42:10.184  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 11:42:10.184  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-08 11:42:10.184  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:42:10.184  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 11:42:10.184  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 11:42:10.184  5645  5698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 11:42:10.187  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 11:42:10.187  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 11:42:10.187  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 11:42:10.188  5645  5698 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:42:10.191  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 11:42:10.192  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-08 11:42:10.192  5645  5698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-08 11:42:10.192  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 11:42:10.186  4692  4692 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[28621]" dev="sockfs" ino=28621 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 11:42:10.190  4692  4692 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[28621]" dev="sockfs" ino=28621 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:42:10.194  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.194  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:42:10.194  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:42:10.194  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
,11-08 11:42:10.194  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:42:10.195  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.195  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.195  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.195  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:10.195  5645  5692 D BluetoothAdapter: STATE_ON
,11-08 11:42:10.199  4679  4692 D BtGatt.GattService: registerClient() - UUID=7aef1454-7333-4616-8fda-0bd79f30897b
,11-08 11:42:10.199  4679  4752 D BtGatt.GattService: onClientRegistered() - UUID=7aef1454-7333-4616-8fda-0bd79f30897b, clientIf=5
,11-08 11:42:10.200  5645  5656 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 11:42:10.202  4679  4754 D BtGatt.AdvertiseManager: message : 0
,11-08 11:42:10.205  4679  4754 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 11:42:10.220  4679  4752 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 11:42:10.227  4679  4752 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 11:42:10.228  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:10.228  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.228  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 11:42:10.228  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.228  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.228  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.228  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.229  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.229  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-08 11:42:10.229  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:42:10.230  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:10.230  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.230  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.230  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.231  5645  5692 I io.jxcore.node.ConnectionHelper: start: OK
11-08 11:42:10.231  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-08 11:42:10.231  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.232  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:10.232  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:42:10.232  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.232  5645  5645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:10.232  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.232  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 11:42:10.233  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 11:42:10.233  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.233  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.233  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 11:42:10.233  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 11:42:10.236  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.236  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 11:42:10.236  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.237  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.237  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.237  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:10.237  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 11:42:10.737  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-08 11:42:10.737  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-08 11:42:10.737  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-08 11:42:10.737  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-08 11:42:10.737  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-08 11:42:10.737  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-08 11:42:10.737  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-08 11:42:10.737  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-08 11:42:10.738  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-08 11:42:10.738  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-08 11:42:10.738  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-08 11:42:10.738  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-08 11:42:10.738  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-08 11:42:10.738  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-08 11:42:10.738  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-08 11:42:10.738  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-08 11:42:10.738  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 11:42:10.739  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-08 11:42:10.739  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-08 11:42:10.739  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-08 11:42:10.739  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 11:42:10.739  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-08 11:42:10.739  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-08 11:42:10.739  5645  5645 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 11:42:10.739  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-08 11:42:10.739  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-08 11:42:10.740  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-08 11:42:10.740  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-08 11:42:10.740  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-08 11:42:10.740  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-08 11:42:10.740  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-08 11:42:10.740  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-08 11:42:10.740  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-08 11:42:10.740  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-08 11:42:10.740  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-08 11:42:10.741  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-08 11:42:10.741  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 11:42:10.741  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 11:42:10.741  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 11:42:10.741  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 11:42:10.742  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 11:42:10.742  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 11:42:10.742  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 11:42:10.742  5645  5698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 11:42:10.742  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-08 11:42:10.742  5645  5698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 11:42:10.742  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-08 11:42:10.743  5645  5698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 11:42:10.743  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 11:42:10.743  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 11:42:10.743  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 11:42:10.744  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.744  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.745  5645  5692 D BluetoothAdapter: STATE_ON
11-08 11:42:10.745  5645  5692 D BluetoothLeScanner: could not find callback wrapper
11-08 11:42:10.745  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-08 11:42:10.745  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.746  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.746  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 11:42:10.746  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.747  4679  4754 D BtGatt.AdvertiseManager: message : 1
11-08 11:42:10.748  4679  4754 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 11:42:10.762  4679  4752 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 11:42:10.762  4679  4752 D BtGatt.GattService: Client app is not null!
11-08 11:42:10.763  4679  4891 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 11:42:10.764  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 11:42:10.765  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.765  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 11:42:10.765  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.765  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:10.765  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.765  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 11:42:10.765  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 11:42:10.765  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:10.765  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.766  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 11:42:10.766  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.767  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.767  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:42:10.767  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.767  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.767  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.767  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:10.768  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.768  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 11:42:10.768  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-08 11:42:10.769  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 11:42:10.769  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:10.770  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.770  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.771  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.771  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 11:42:10.771  5645  5645 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 11:42:10.771  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:10.771  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:42:10.772  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:42:10.772  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:10.772  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:42:10.773  5645  5692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 11:42:10.773  5645  5692 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 11:42:10.773  5645  5692 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-08 11:42:10.773  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-08 11:42:10.774  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:42:10.774  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 11:42:10.774  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 11:42:10.774  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:42:10.775  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 11:42:10.776  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 11:42:10.776  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 11:42:10.776  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 11:42:10.776  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-08 11:42:10.776  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 11:42:10.777  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:42:10.777  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 11:42:10.777  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 11:42:10.781  5645  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 11:42:10.782  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 11:42:10.782  5645  5701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:42:10.782  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 11:42:10.782  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 11:42:10.788  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 11:42:10.783  4690  4690 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[28628]" dev="sockfs" ino=28628 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:42:10.783  4690  4690 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[28628]" dev="sockfs" ino=28628 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:42:10.788  5645  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 11:42:10.789  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 11:42:10.789  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 11:42:10.791  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.791  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:42:10.791  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:42:10.792  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-08 11:42:10.792  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:42:10.792  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.792  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.792  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.792  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.793  5645  5692 D BluetoothAdapter: STATE_ON
11-08 11:42:10.797  4679  4690 D BtGatt.GattService: registerClient() - UUID=3adfe534-02cb-4816-801d-ce7de271f2e2
11-08 11:42:10.798  4679  4752 D BtGatt.GattService: onClientRegistered() - UUID=3adfe534-02cb-4816-801d-ce7de271f2e2, clientIf=5
11-08 11:42:10.798  5645  5656 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 11:42:10.799  4679  4754 D BtGatt.AdvertiseManager: message : 0
11-08 11:42:10.802  4679  4754 D BtGatt.AdvertiseManager: starting multi advertising
11-08 11:42:10.816  4679  4752 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 11:42:10.824  4679  4752 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-08 11:42:10.824  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.825  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.825  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 11:42:10.825  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.825  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.825  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.825  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.826  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.826  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 11:42:10.828  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:42:10.828  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.830  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.830  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.830  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:10.830  5645  5692 I io.jxcore.node.ConnectionHelper: start: OK
11-08 11:42:10.830  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:42:10.830  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.830  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:10.831  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:42:10.831  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.831  5645  5645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:10.831  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.831  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 11:42:10.831  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 11:42:10.831  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.831  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.831  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 11:42:10.831  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.835  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.835  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 11:42:10.835  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.835  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.835  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:42:10.835  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:10.836  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 11:42:11.334  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-08 11:42:11.334  5645  5692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 11:42:11.335  5645  5692 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 11:42:11.335  5645  5692 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-08 11:42:11.335  5645  5692 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-08 11:42:11.336  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-08 11:42:11.336  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-08 11:42:11.336  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-08 11:42:11.336  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-08 11:42:11.336  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-08 11:42:11.336  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-08 11:42:11.336  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-08 11:42:11.336  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-08 11:42:11.336  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-08 11:42:11.336  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-08 11:42:11.336  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.337  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 11:42:11.341  4679  4754 D BtGatt.AdvertiseManager: message : 1
11-08 11:42:11.342  4679  4754 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 11:42:11.357  4679  4752 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 11:42:11.357  4679  4752 D BtGatt.GattService: Client app is not null!
,11-08 11:42:11.358  4679  4924 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 11:42:11.359  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 11:42:11.359  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.359  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 11:42:11.359  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.360  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.360  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 11:42:11.360  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.360  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:42:11.360  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 11:42:11.360  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-08 11:42:11.361  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:42:11.361  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.361  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.361  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.362  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.363  5645  5692 D BluetoothAdapter: STATE_ON
,11-08 11:42:11.366  4679  4891 D BtGatt.GattService: registerClient() - UUID=3994fd12-9b1a-463f-aa51-60d062deb650
11-08 11:42:11.369  4679  4752 D BtGatt.GattService: onClientRegistered() - UUID=3994fd12-9b1a-463f-aa51-60d062deb650, clientIf=5
11-08 11:42:11.369  5645  5656 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 11:42:11.371  4679  4754 D BtGatt.AdvertiseManager: message : 0
11-08 11:42:11.377  4679  4754 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 11:42:11.395  4679  4752 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 11:42:11.405  4679  4752 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 11:42:11.406  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.407  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.407  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 11:42:11.407  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.407  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.407  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.407  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.407  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.407  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 11:42:11.408  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 11:42:11.408  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 11:42:11.408  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-08 11:42:11.408  5645  5692 I io.jxcore.node.ConnectionHelper: start: OK
11-08 11:42:11.409  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-08 11:42:11.409  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:11.409  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:42:11.409  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
,11-08 11:42:11.409  5645  5645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:11.409  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-08 11:42:11.409  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 11:42:11.410  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 11:42:11.410  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-08 11:42:11.410  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:42:11.410  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:11.410  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-08 11:42:11.410  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-08 11:42:11.410  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 11:42:11.410  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 11:42:11.410  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-08 11:42:11.411  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 11:42:11.411  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 11:42:11.411  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-08 11:42:11.411  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 11:42:11.411  5645  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 11:42:11.411  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-08 11:42:11.411  5645  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 11:42:11.411  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 11:42:11.411  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-08 11:42:11.411  5645  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 11:42:11.411  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 11:42:11.411  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-08 11:42:11.412  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.412  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.413  5645  5692 D BluetoothAdapter: STATE_ON
,11-08 11:42:11.413  5645  5692 D BluetoothLeScanner: could not find callback wrapper
11-08 11:42:11.413  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 11:42:11.413  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.413  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.414  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 11:42:11.414  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.416  4679  4754 D BtGatt.AdvertiseManager: message : 1
,11-08 11:42:11.416  4679  4754 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 11:42:11.425  4679  4752 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 11:42:11.425  4679  4752 D BtGatt.GattService: Client app is not null!
,11-08 11:42:11.427  4679  4692 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 11:42:11.428  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 11:42:11.428  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.428  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 11:42:11.428  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.428  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.428  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.428  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 11:42:11.429  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 11:42:11.429  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.429  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.429  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 11:42:11.429  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.431  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.431  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:42:11.431  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.431  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.431  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.431  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.431  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.432  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 11:42:11.432  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-08 11:42:11.433  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 11:42:11.433  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.434  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.435  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.435  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.436  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-08 11:42:11.436  5645  5645 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 11:42:11.436  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:42:11.436  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:42:11.437  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:11.437  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:11.437  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:42:11.439  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-08 11:42:11.439  5645  5692 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-08 11:42:11.440  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-08 11:42:11.441  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-08 11:42:11.441  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-08 11:42:11.442  5645  5692 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-08 11:42:11.443  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-08 11:42:11.443  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-08 11:42:11.443  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-08 11:42:11.444  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 11:42:11.444  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-08 11:42:11.444  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:42:11.444  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:42:11.444  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-08 11:42:11.444  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:42:11.444  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:42:11.444  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:42:11.444  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 11:42:11.444  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-08 11:42:11.444  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:42:11.444  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 11:42:11.445  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-08 11:42:11.446  5645  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-08 11:42:11.446  5645  5692 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-08 11:42:11.450  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-08 11:42:11.450  5645  5692 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-08 11:42:11.453  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,11-08 11:42:11.453  5645  5692 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-08 11:42:11.454  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-08 11:42:11.455  5645  5692 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-08 11:42:11.455  5645  5692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-08 11:42:11.455  5645  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-08 11:42:11.455  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-08 11:42:11.455  5645  5692 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-08 11:42:11.455  5645  5692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-08 11:42:11.455  5645  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-08 11:42:11.455  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 11:42:11.455  5645  5692 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-08 11:42:11.455  5645  5692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-08 11:42:11.455  5645  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,11-08 11:42:11.455  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 11:42:11.456  5645  5692 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-08 11:42:11.456  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-08 11:42:11.456  5645  5692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 11:42:11.456  5645  5692 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 11:42:11.456  5645  5692 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-08 11:42:11.456  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-08 11:42:11.457  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:42:11.457  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 11:42:11.457  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 11:42:11.457  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:42:11.458  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 11:42:11.459  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 11:42:11.459  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 11:42:11.459  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 11:42:11.459  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 11:42:11.459  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 11:42:11.459  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:42:11.459  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 11:42:11.459  5645  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 11:42:11.459  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 11:42:11.460  5645  5705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:42:11.460  4692  4692 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[30584]" dev="sockfs" ino=30584 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 11:42:11.463  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 11:42:11.463  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-08 11:42:11.460  4692  4692 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[30584]" dev="sockfs" ino=30584 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:42:11.463  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 11:42:11.464  5645  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 11:42:11.469  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 11:42:11.470  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 11:42:11.470  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 11:42:11.472  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.472  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:42:11.472  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:42:11.472  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-08 11:42:11.473  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:42:11.473  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.473  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.473  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.473  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.474  5645  5692 D BluetoothAdapter: STATE_ON
11-08 11:42:11.477  4679  4690 D BtGatt.GattService: registerClient() - UUID=f221f69f-291e-49b6-83bf-eb7163045030
11-08 11:42:11.477  4679  4752 D BtGatt.GattService: onClientRegistered() - UUID=f221f69f-291e-49b6-83bf-eb7163045030, clientIf=5
11-08 11:42:11.478  5645  5656 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 11:42:11.479  4679  4754 D BtGatt.AdvertiseManager: message : 0
,11-08 11:42:11.481  4679  4754 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 11:42:11.490  4679  4752 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 11:42:11.496  4679  4752 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 11:42:11.497  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.497  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.497  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 11:42:11.497  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.497  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.497  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.497  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.498  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.498  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-08 11:42:11.499  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:42:11.499  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.500  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:11.500  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.500  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:11.500  5645  5692 I io.jxcore.node.ConnectionHelper: start: OK
11-08 11:42:11.501  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:42:11.501  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 11:42:11.501  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:11.501  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:42:11.501  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 11:42:11.501  5645  5645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:11.501  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 11:42:11.501  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 11:42:11.501  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 11:42:11.501  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 11:42:11.501  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-08 11:42:11.502  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 11:42:11.502  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 11:42:11.504  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 11:42:11.505  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 11:42:11.505  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-08 11:42:11.505  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 11:42:11.505  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:42:11.505  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:11.505  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 11:42:12.002  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-08 11:42:12.002  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 11:42:12.003  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 11:42:12.003  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-08 11:42:12.003  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 11:42:12.003  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 11:42:12.003  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 11:42:12.004  5645  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 11:42:12.004  5645  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-08 11:42:12.004  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-08 11:42:12.004  5645  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 11:42:12.004  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@acec83c removed from the list
11-08 11:42:12.004  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 11:42:12.004  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-08 11:42:12.004  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 11:42:12.004  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:42:12.004  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 11:42:12.005  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:42:12.005  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-08 11:42:12.005  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 11:42:12.005  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.005  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.008  5645  5692 D BluetoothAdapter: STATE_ON
11-08 11:42:12.008  5645  5692 D BluetoothLeScanner: could not find callback wrapper
,11-08 11:42:12.008  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 11:42:12.008  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.009  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.009  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-08 11:42:12.009  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.012  4679  4754 D BtGatt.AdvertiseManager: message : 1
11-08 11:42:12.013  4679  4754 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 11:42:12.027  4679  4752 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 11:42:12.028  4679  4752 D BtGatt.GattService: Client app is not null!
,11-08 11:42:12.029  4679  4924 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 11:42:12.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 11:42:12.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-08 11:42:12.031  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.031  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.031  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.031  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 11:42:12.031  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 11:42:12.031  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.032  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.032  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 11:42:12.032  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.034  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.034  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:42:12.034  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:12.035  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.035  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.035  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.035  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.035  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 11:42:12.035  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 11:42:12.036  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 11:42:12.037  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.040  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.040  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.040  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:12.040  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@575b9c5 removed from the list
11-08 11:42:12.040  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:12.041  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
,11-08 11:42:12.041  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:12.041  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 11:42:12.041  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 11:42:12.542  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 11:42:17.045  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-08 11:42:17.047  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-08 11:42:17.047  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:42:17.050  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-08 11:42:17.051  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-08 11:42:17.051  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 11:42:17.051  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-08 11:42:17.052  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 11:42:17.052  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-08 11:42:17.052  5645  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 11:42:17.052  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 11:42:17.060  4924  4924 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32381]" dev="sockfs" ino=32381 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:42:17.055  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-08 11:42:17.060  4924  4924 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32381]" dev="sockfs" ino=32381 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:42:17.056  5645  5692 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-08 11:42:17.057  5645  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-08 11:42:17.057  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-08 11:42:17.057  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:42:17.057  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 11:42:17.059  5645  5706 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:42:17.059  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-08 11:42:17.064  5645  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-08 11:42:17.067  5645  5692 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-08 11:42:17.068  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-08 11:42:17.068  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-08 11:42:17.068  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-08 11:42:17.068  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-08 11:42:17.069  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 11:42:17.069  5645  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 11:42:17.069  5645  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 11:42:17.069  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 11:42:17.069  5645  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-08 11:42:17.069  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 11:42:17.069  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@acec83c not in the list
11-08 11:42:17.069  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:42:17.069  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-08 11:42:17.069  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 11:42:17.069  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:42:17.069  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-08 11:42:17.069  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 11:42:17.069  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 11:42:17.069  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 11:42:17.069  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 11:42:17.069  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:17.072  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:17.072  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:42:17.072  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:17.072  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:17.072  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@575b9c5 not in the list
11-08 11:42:17.072  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:17.072  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
,11-08 11:42:17.072  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 11:42:17.072  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:17.072  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 11:42:17.072  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:42:17.074  5645  5692 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-08 11:42:17.074  5645  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-08 11:42:17.074  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-08 11:42:17.074  5645  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-08 11:42:17.074  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-08 11:42:17.074  5645  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-08 11:42:17.075  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 11:42:17.075  5645  5692 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-08 11:42:17.076  5645  5692 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-08 11:42:17.078  5645  5692 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-08 11:42:17.078  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-08 11:42:17.078  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-08 11:42:17.079  5645  5692 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-08 11:42:17.079  5645  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-08 11:42:17.079  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-08 11:42:17.080  5645  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-08 11:42:17.080  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-08 11:42:17.080  5645  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-08 11:42:17.081  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-08 11:42:17.081  5645  5692 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-08 11:42:17.082  5645  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-08 11:42:17.082  5645  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-08 11:42:17.083  5645  5692 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-08 11:42:17.083  5645  5692 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-08 11:42:17.083  5645  5692 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-08 11:42:17.083  5645  5692 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-08 11:42:17.083  5645  5692 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-08 11:42:17.084  5645  5692 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-08 11:42:17.085  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-08 11:42:17.085  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8919e35 added. We now have 3 listener(s)
11-08 11:42:17.086  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:42:17.086  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 11:42:17.086  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 11:42:17.086  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 11:42:17.086  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@632b2ca added. We now have 3 listener(s)
11-08 11:42:17.087  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-08 11:42:17.087  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 11:42:17.091  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:42:17.095  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:42:17.095  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:17.095  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:17.095  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:17.095  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:17.095  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:42:17.095  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:42:17.095  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 11:42:17.096  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 11:42:17.096  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
11-08 11:42:17.098  5645  5692 D BluetoothAdapter: enable(): BT is already enabled..!
11-08 11:42:17.098   929  3858 D WifiService: setWifiEnabled: true pid=5645, uid=10077
11-08 11:42:17.098   929  3858 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 11:42:17.099  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:17.100  5645  5692 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-08 11:42:17.101  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:17.102  5645  5692 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
11-08 11:42:17.103  5645  5692 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-08 11:42:17.106   929   940 D WifiService: setWifiEnabled: false pid=5645, uid=10077
11-08 11:42:17.106   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:42:17.110   929  2985 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-08 11:42:17.110   929  2985 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-08 11:42:17.110   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 11:42:17.111   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 11:42:17.118   929  5409 D DhcpClient: Clearing IP address
11-08 11:42:17.118   509   927 D CommandListener: Clearing all IP addresses on wlan0
,11-08 11:42:17.126   509   927 D CommandListener: Setting iface cfg
,11-08 11:42:17.127   929  5410 D DhcpClient: Receive thread stopped
11-08 11:42:17.132  3595  5460 V NativeCrypto: Read error: ssl=0x7f7836e700: I/O error during system call, Connection timed out
,11-08 11:42:17.133   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-08 11:42:17.133   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-08 11:42:17.134  3595  5460 V NativeCrypto: SSL shutdown failed: ssl=0x7f7836e700: I/O error during system call, Broken pipe
11-08 11:42:17.140   542   542 E Parcel  : Reading a NULL string not supported here.
,11-08 11:42:17.140   929   929 D RttService: SCAN_AVAILABLE : 1
11-08 11:42:17.140   929  3094 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-08 11:42:17.140   929  2987 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-08 11:42:17.145  3777  3900 W QCNEJ   : |CORE| network lost: 100
11-08 11:42:17.146  3777  3900 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-08 11:42:17.148   929  3449 I ActivityManager: Killing 5447:com.android.chrome/u0a39 (adj 15): empty #17
,11-08 11:42:17.152   929  2985 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-08 11:42:17.170   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 11:42:17.191   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 11:42:17.192   509   927 D TetherController: Setting IP forward enable = 0
,11-08 11:42:17.192   929  2987 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-08 11:42:17.193   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-08 11:42:17.198   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 11:42:17.200   509   927 D CommandListener: Clearing all IP addresses on wlan0
,11-08 11:42:17.202   929   946 D Tethering: MasterInitialState.processMessage what=3
11-08 11:42:17.206  5307  5307 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f40916 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-08 11:42:17.209  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:17.209  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:17.209  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:17.209  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:17.209  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:17.209  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:17.209  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:17.209  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:17.210  3994  3994 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-08 11:42:17.211  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:17.218  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:17.218  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:17.218  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:17.218  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:17.218  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:17.218  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:17.218  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:17.218  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:17.220  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:17.223  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:17.223  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:17.223  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:17.223  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:17.223  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:17.223  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:17.223  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:17.223  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:17.226  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:17.226  4013  4013 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-08 11:42:17.241  4013  4013 D SystemUpdateService: onCreate
,11-08 11:42:17.244  4013  4013 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-08 11:42:17.247  4013  5726 I SystemUpdateService: active receiver: enabled
,11-08 11:42:17.248   509   927 E Netd    : netlink response contains error (No such file or directory)
,11-08 11:42:17.249   509   927 D TetherController: Setting IP forward enable = 0
11-08 11:42:17.250   929  2985 D DhcpClient: doQuit
,11-08 11:42:17.251   929  2985 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-08 11:42:17.251  3486  3486 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-08 11:42:17.252   929  5409 D DhcpClient: onQuitting
,11-08 11:42:17.255  4013  4013 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-08 11:42:17.260  4013  4310 I iu.UploadsManager: num queued entries: 0
11-08 11:42:17.260  4013  4310 I iu.UploadsManager: num updated entries: 0
,11-08 11:42:17.261  4013  4310 I iu.SyncManager: NEXT; no task
,11-08 11:42:17.264  4013  5726 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 11:42:17.264  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:17.264  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:17.264  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:17.264  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:42:17.264  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:17.264  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:17.264  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:17.264  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:17.266  4013  4013 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-08 11:42:17.267  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:17.267  4013  4013 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 11:42:17.269  4013  5726 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-08 11:42:17.269  4013  5726 I SystemUpdateService: now status is 0 (complete)
11-08 11:42:17.269  4013  5726 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-08 11:42:17.269  4013  5726 I SystemUpdateService: file has been verified
11-08 11:42:17.270  4013  5726 I SystemUpdateService: OTA package size = 21989297
11-08 11:42:17.272  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:17.272  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:17.272  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:17.272  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:42:17.272  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:17.272  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:17.272  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:17.272  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:17.275  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:17.275  3486  3486 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-08 11:42:17.279  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:17.279  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:17.279  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:17.279  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:42:17.279  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:17.279  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:17.279  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:17.279  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:17.281  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:17.281   929  3449 I ActivityManager: Start proc 5730:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-08 11:42:17.283  3486  3486 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-08 11:42:17.291  4013  5726 I SystemUpdateService: showing system update notification
,11-08 11:42:17.302   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 11:42:17.304  4013  4013 D SystemUpdateService: onDestroy
,11-08 11:42:17.314  3486  3486 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-08 11:42:17.329  3486  3486 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-08 11:42:17.332  5730  5730 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-08 11:42:17.335  5730  5730 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 11:42:17.340  5730  5730 D SprintDMHelper: simOperator: 
11-08 11:42:17.341  5730  5730 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 11:42:17.353   929  3449 I ActivityManager: Start proc 5742:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-08 11:42:17.354   929  3449 I ActivityManager: Killing 4485:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-08 11:42:17.433   929  2985 D wifi    : In wifi stop Hal
,11-08 11:42:17.433  4506  4506 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 11:42:17.434   929  2985 D wifi    : halHandle = 0x7f61dce080, mVM = 0x7f7e44d140, mCls = 0x100a02
11-08 11:42:17.434   929  3484 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-08 11:42:17.434   929  3484 D WifiHAL : Got a signal to exit!!!
11-08 11:42:17.434   929  3484 I WifiHAL : Exit wifi_event_loop
11-08 11:42:17.434   929  2985 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-08 11:42:17.434   929  2985 E WifiHAL : Event processing terminated
11-08 11:42:17.434   929  2985 D wifi    : In wifi cleaned up handler
11-08 11:42:17.434   929  2985 I WifiHAL : Internal cleanup completed
,11-08 11:42:17.436  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:17.436  3755  4220 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 11:42:17.438  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:17.440  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:17.457   929   939 I ActivityManager: Killing 5154:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-08 11:42:17.460   929  3484 D wifi    : set interface wlan0 flags (DOWN)
,11-08 11:42:17.461   929  2985 D WifiNative-HAL: HAL event thread stopped successfully
,11-08 11:42:17.484   929   939 I ActivityManager: Start proc 5757:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-08 11:42:17.513  5757  5757 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-08 11:42:17.520   929   939 I ActivityManager: Killing 5477:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-08 11:42:17.572  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 11:42:17.611  5645  5707 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:17.614   929  3449 D WifiService: setWifiEnabled: true pid=5645, uid=10077
,11-08 11:42:17.614   929  3449 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:42:17.667   929   946 D Tethering: InitialState.processMessage what=4
11-08 11:42:17.667   509   927 D SoftapController: Softap fwReload - Ok
,11-08 11:42:17.673   509   927 D CommandListener: Setting iface cfg
11-08 11:42:17.673   509   927 D CommandListener: Trying to bring down wlan0
,11-08 11:42:17.675   509   927 D CommandListener: Clearing all IP addresses on wlan0
11-08 11:42:17.677   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-08 11:42:17.680   929  2985 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 11:42:18.121   929  3138 D WifiService: setWifiEnabled: true pid=5645, uid=10077
,11-08 11:42:18.123   929  3138 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:42:18.287   929  2985 D wifi    : set interface wlan0 flags (UP)
,11-08 11:42:18.287   929  2985 I WifiHAL : Initializing wifi
11-08 11:42:18.288   929  2985 I WifiHAL : Creating socket
,11-08 11:42:18.295   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-08 11:42:18.295   929  2985 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-08 11:42:18.296   929  2985 D wifi    : Did set static halHandle = 0x7f61dce080
,11-08 11:42:18.296   929  2985 D wifi    : halHandle = 0x7f61dce080, mVM = 0x7f7e44d140, mCls = 0x2014d2
11-08 11:42:18.296   929  2985 D wifi    : array field set
,11-08 11:42:18.296   929  2985 I WifiNative-HAL: interface[0] = wlan0
11-08 11:42:18.298   929  5772 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547102711936
,11-08 11:42:18.298   929  5772 D wifi    : waitForHalEvents called, vm = 0x7f7e44d140, obj = 0x2014d2, env = 0x7f639ade40
,11-08 11:42:18.370  5773  5773 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-08 11:42:18.400   929  2985 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-08 11:42:18.408  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:18.411  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:18.413  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:18.439  5773  5773 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 11:42:18.444  5773  5773 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-08 11:42:18.444  5773  5773 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-08 11:42:18.456   929  2985 D WifiConfigStore: Loading config and enabling all networks 
,11-08 11:42:18.464  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:18.464  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:18.464  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:18.464  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:18.464  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:18.464  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:18.464  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:18.464  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:18.468  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:18.470   929  2985 D WifiConfigStore: loaded 0 passpoint configs
11-08 11:42:18.471   929  2985 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-08 11:42:18.471   929  2985 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-08 11:42:18.471   929  2985 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-08 11:42:18.472   929  2985 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-08 11:42:18.472   929  2985 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-08 11:42:18.472   929  2985 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-08 11:42:18.473   929  2985 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-08 11:42:18.473   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-08 11:42:18.473   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-08 11:42:18.473   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-08 11:42:18.473   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-08 11:42:18.473   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-08 11:42:18.475   929  2985 D WifiNative-HAL: Setting external_sim to 1
,11-08 11:42:18.475  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:18.475  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:18.475  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:18.475  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:18.475  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:18.475  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:18.475  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:18.475  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:18.475   929  2985 D wifi    : setting dfs flag to true, 0x7f63682b80
11-08 11:42:18.475   929  2985 D WifiStateMachine: Setting OUI to DA-A1-19
11-08 11:42:18.475   929  2985 D wifi    : setting scan oui 0x7f63682b80
11-08 11:42:18.475   929  2985 D WifiHAL : Sending mac address OUI
11-08 11:42:18.476  4506  4506 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 11:42:18.478   929  2985 E native  : do suspend false
,11-08 11:42:18.479  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:18.485   929  2985 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-08 11:42:18.485   929   929 D RttService: SCAN_AVAILABLE : 3
11-08 11:42:18.486   929  3094 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-08 11:42:18.487  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:18.487  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:18.487  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:18.487  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:18.487  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:18.487  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:18.487  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:18.487  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:42:18.490   509   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-08 11:42:18.491   509   927 D CommandListener: Setting iface cfg
11-08 11:42:18.492   929  2984 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
11-08 11:42:18.492   929  2984 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
11-08 11:42:18.494  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:18.495   929  2984 D WifiNative-HAL: p2pGetDeviceAddress
,11-08 11:42:18.500   929  2984 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-08 11:42:18.521   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=106066 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=31 mControllerEnergyUsed=117 }
,11-08 11:42:18.629  5645  5707 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:18.645  4679  4746 D BluetoothAdapterState: Current state: ON, message: 23
,11-08 11:42:18.645  4679  4746 D BluetoothAdapterProperties: Setting state to 13
,11-08 11:42:18.645  4679  4746 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-08 11:42:18.647  4679  4746 D BluetoothAdapterProperties: onBluetoothDisable()
,11-08 11:42:18.648  4679  4746 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:42:18.657  4679  4679 D BluetoothMapService: onReceive
,11-08 11:42:18.657  4679  4679 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-08 11:42:18.658  4679  4679 D BluetoothMapService: STATE_TURNING_OFF
11-08 11:42:18.658  4679  4679 D BluetoothMapService: MAP Service closeService in
11-08 11:42:18.658  4679  4679 D BluetoothMapMasInstance0: MAP Service shutdown
11-08 11:42:18.658  4679  4679 D ObexServerSockets0: shutdown(block = true)
11-08 11:42:18.660  4679  4679 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-08 11:42:18.660  4679  4889 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-08 11:42:18.661  4679  4679 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 11:42:18.661  4679  4926 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-08 11:42:18.661  4679  4925 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-08 11:42:18.661  4679  4752 D BluetoothAdapterProperties: Scan Mode:20
11-08 11:42:18.662  4679  4746 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-08 11:42:18.663  4679  4679 I BtOppRfcommListener: stopping Accept Thread
11-08 11:42:18.663  4679  5333 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-08 11:42:18.663  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:42:18.664  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:18.664  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:18.664  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:18.664  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:18.664  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:42:18.664  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:18.664  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:18.664  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:42:18.664  4679  5333 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-08 11:42:18.669  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:42:18.669  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:18.673  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:42:18.673  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:18.673  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:18.673  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:18.673  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:18.673  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:42:18.673  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:18.673  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:18.673  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:18.674  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:42:18.674  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:18.678  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 11:42:18.678  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:18.678  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:18.678  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:18.678  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:18.678  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:42:18.678  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:18.678  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:18.678  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:18.679  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 11:42:18.679  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:18.681  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:18.683  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:18.685  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:18.687   929   942 I ActivityManager: Start proc 5777:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-08 11:42:18.689  4679  4679 D HeadsetService: Received stop request...Stopping profile...
,11-08 11:42:18.692   929   929 D BluetoothHeadset: Proxy object disconnected
,11-08 11:42:18.694  3146  3172 D BluetoothHeadset: Proxy object disconnected
11-08 11:42:18.694   929   929 D BluetoothHeadset: Proxy object disconnected
11-08 11:42:18.695  3816  4050 D BluetoothHeadset: Proxy object disconnected
11-08 11:42:18.695   929   929 D BluetoothHeadset: Proxy object disconnected
11-08 11:42:18.699  4679  4679 D A2dpService: Received stop request...Stopping profile...
11-08 11:42:18.699  4679  4895 D A2dpStateMachine: Exit Disconnected: -1
,11-08 11:42:18.702  4679  4679 V BluetoothAdapterState: isTurningOff()=true
,11-08 11:42:18.701   929   929 D BluetoothA2dp: Proxy object disconnected
11-08 11:42:18.702  4679  4679 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:18.702  4679  4679 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:18.703  4679  4679 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 11:42:18.705  4679  4679 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-08 11:42:18.705  4679  4679 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-08 11:42:18.705  4679  4752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-08 11:42:18.706  4679  4884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:42:18.706  4679  4884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:42:18.706  4679  4884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:42:18.706  4679  4752 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-08 11:42:18.707  4679  4679 D HidService: Received stop request...Stopping profile...
11-08 11:42:18.707  4679  4679 D HidService: Stopping Bluetooth HidService
11-08 11:42:18.709  4679  4679 D HealthService: Received stop request...Stopping profile...
11-08 11:42:18.710  4679  4679 D PanService: Received stop request...Stopping profile...
11-08 11:42:18.711  4679  4679 D BluetoothMapService: Received stop request...Stopping profile...
11-08 11:42:18.711  4679  4679 D BluetoothMapService: stop()
11-08 11:42:18.712  4679  4679 D BluetoothMapAppObserver: deinitObservers()
11-08 11:42:18.712  4679  4679 D BluetoothMapAppObserver: removeReceiver()
11-08 11:42:18.713  3146  3146 D HeadsetProfile: Bluetooth service disconnected
11-08 11:42:18.713  3146  3146 D BluetoothA2dp: Proxy object disconnected
11-08 11:42:18.713  3146  3146 D BluetoothInputDevice: Proxy object disconnected
11-08 11:42:18.713  3146  3146 D HidProfile: Bluetooth service disconnected
11-08 11:42:18.713  3146  3146 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 11:42:18.713  3146  3146 D PanProfile: Bluetooth service disconnected
11-08 11:42:18.713  3146  3146 D BluetoothMap: Proxy object disconnected
11-08 11:42:18.714  3146  3146 D MapProfile: Bluetooth service disconnected
11-08 11:42:18.714  4679  4679 V BluetoothAdapterState: isTurningOff()=true
11-08 11:42:18.714  4679  4679 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:18.714  4679  4679 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:18.714  4679  4679 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:18.715  4679  4752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-08 11:42:18.716  4679  4884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:42:18.716  4679  4884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:42:18.716  4679  4884 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 11:42:18.716  4679  4884 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 11:42:18.716  4679  4884 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 11:42:18.716  4679  4884 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-08 11:42:18.722  4679  4679 D SapService: Received stop request...Stopping profile...
11-08 11:42:18.722  4679  4679 V SapService: stop()
,11-08 11:42:18.724  4679  4679 V BluetoothAdapterState: isTurningOff()=true
,11-08 11:42:18.724  4679  4679 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:18.724  4679  4679 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:18.724  4679  4679 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:18.724  4679  4679 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-08 11:42:18.724  4679  4679 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-08 11:42:18.724  4679  4752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 11:42:18.724  4679  4679 V BluetoothAdapterState: isTurningOff()=true
,11-08 11:42:18.724  4679  4679 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:18.724  4679  4679 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:18.724  4679  4679 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:18.725  4679  4679 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-08 11:42:18.725  4679  4752 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-08 11:42:18.725  4679  4679 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-08 11:42:18.725  4679  4679 V BluetoothAdapterState: isTurningOff()=true
11-08 11:42:18.725  4679  4679 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:18.725  4679  4679 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:18.725  4679  4679 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 11:42:18.726  4679  4679 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-08 11:42:18.726  4679  4679 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-08 11:42:18.726  4679  4679 D BluetoothMapService: MAP Service closeService in
11-08 11:42:18.727  4679  4679 V BluetoothAdapterState: isTurningOff()=true
11-08 11:42:18.727  4679  4679 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:18.727  4679  4679 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:18.727  4679  4679 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:18.727  4679  4679 D BluetoothMapService: cleanup()
11-08 11:42:18.727  4679  4679 D BluetoothMapService: MAP Service closeService in
11-08 11:42:18.727  4679  4679 V BluetoothAdapterState: isTurningOff()=true
,11-08 11:42:18.727  4679  4679 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:18.727  4679  4679 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:18.727  4679  4679 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:18.728  4679  4746 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-08 11:42:18.728  4679  4746 D BluetoothAdapterProperties: Setting state to 15
11-08 11:42:18.728  4679  4746 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-08 11:42:18.729  4679  4746 I BluetoothAdapterState: Entering BleOnState
,11-08 11:42:18.729   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 11:42:18.729  3146  4048 D BluetoothMap: onBluetoothStateChange: up=false
11-08 11:42:18.730   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:42:18.730  3146  3169 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 11:42:18.731   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:42:18.732  3146  3172 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:42:18.732  3816  4332 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:42:18.733  3146  4048 D BluetoothPan: onBluetoothStateChange on: false
,11-08 11:42:18.734   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-08 11:42:18.734  3146  3169 D BluetoothPbap: onBluetoothStateChange: up=false
,11-08 11:42:18.735  3146  4048 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 11:42:18.736  4679  4746 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-08 11:42:18.736  4679  4746 D BluetoothAdapterProperties: Setting state to 16
11-08 11:42:18.736  4679  4746 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-08 11:42:18.737  4679  4746 D BluetoothAdapterProperties: onBleDisable
,11-08 11:42:18.737  4679  4746 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:42:18.738  4679  4747 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-08 11:42:18.739  4679  4752 D BluetoothAdapterProperties: Scan Mode:20
,11-08 11:42:18.740  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:18.740  4679  4884 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-08 11:42:18.740  4679  4884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:42:18.741  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:18.742  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:18.744  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:18.745  5777  5777 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-08 11:42:18.746  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:18.747  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:18.762  5777  5777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-08 11:42:18.767   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@68d5fd7:true
,11-08 11:42:18.767  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 11:42:18.781   929  3182 I ActivityManager: Start proc 5789:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-08 11:42:18.793  5777  5777 D LocalBluetoothProfileManager: Adding local MAP profile
11-08 11:42:18.797  5777  5777 D BluetoothMap: Create BluetoothMap proxy object
11-08 11:42:18.810  5777  5777 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-08 11:42:18.819  5789  5789 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-08 11:42:18.828  5777  5777 D DockEventReceiver: finishStartingService: stopping service
,11-08 11:42:18.831   929   940 I ActivityManager: Killing 5307:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-08 11:42:18.948  4679  4752 I bt_hci  : shut_down
,11-08 11:42:18.951  4679  4756 D bt_hwcfg: hw_epilog_process
,11-08 11:42:18.952  4679  4756 I bt_vendor: low_power_mode_cb
,11-08 11:42:18.954  4679  4756 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-08 11:42:18.954  4679  4756 I bt_vendor: epilog_cb
11-08 11:42:18.954  4679  4756 I bt_hci  : epilog_finished_callback
,11-08 11:42:18.958  4679  4752 I bt_hci_h4: hal_close
,11-08 11:42:18.958  4679  4752 I bt_userial_vendor: device fd = 54 close
,11-08 11:42:19.066  4679  4747 D bt_stack_manager: event_shut_down_stack finished.
,11-08 11:42:19.067  4679  4746 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-08 11:42:19.069  4679  4746 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-08 11:42:19.069  4679  4679 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-08 11:42:19.069  4679  4679 D BtGatt.GattService: Received stop request...Stopping profile...
11-08 11:42:19.070  4679  4679 D BtGatt.GattService: stop()
,11-08 11:42:19.070  4679  4679 D BtGatt.AdvertiseManager: advertise clients cleared
11-08 11:42:19.070  5789  5789 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:42:19.070  5789  5789 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693,)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:42:19.070  5789  5789 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.Looper.loop(Looper.java:14,8)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:42:19.070  5789  5789 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.e.b(PG:170)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:42:19.070  5789  5789 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.k.d(PG:583)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.e.b(PG:170)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:42:19.070  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:42:19.071  5789  5789 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:42:19.071  5789  5789 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:42:19.071  5789  5789 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:42:19.071  5789  5789 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:42:19.071  4679  4679 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:19.071  4679  4679 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:19.072  4679  4679 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:19.072  4679  4679 V BluetoothAdapterState: isBleTurningOff()=true
11-08 11:42:19.072  4679  4746 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-08 11:42:19.072  4679  4746 D BluetoothAdapterProperties: Setting state to 10
11-08 11:42:19.072  4679  4746 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-08 11:42:19.073  4679  4746 I BluetoothAdapterState: Entering OffState
11-08 11:42:19.074   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-08 11:42:19.082  4679  4679 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-08 11:42:19.082  4679  4679 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-08 11:42:19.082  4679  4679 I BluetoothServiceJni: cleanupNative: return from cleanup
11-08 11:42:19.084  4679  4747 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-08 11:42:19.093  4679  4747 D bt_stack_manager: event_clean_up_stack finished.
11-08 11:42:19.094  4679  4679 I art     : System.exit called, status: 0
11-08 11:42:19.094  4679  4679 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-08 11:42:19.127  5777  5777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 11:42:19.130   929  3182 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
11-08 11:42:19.131   929  3182 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
11-08 11:42:19.132   929  3182 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
11-08 11:42:19.132   929  3182 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-08 11:42:19.132   929  3182 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
11-08 11:42:19.132   929  3182 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
11-08 11:42:19.132   929  3182 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
11-08 11:42:19.132   929  3182 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
11-08 11:42:19.132   929  3182 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
11-08 11:42:19.132   929  3182 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
11-08 11:42:19.132   929  3182 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
11-08 11:42:19.132   929  3182 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
11-08 11:42:19.132   929  3182 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
11-08 11:42:19.143  5645  5707 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:19.155   929  3182 I ActivityManager: Start proc 5822:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,11-08 11:42:19.156  5777  5777 D DockEventReceiver: finishStartingService: stopping service
,11-08 11:42:19.156   929  3449 W ActivityManager: Spurious death for ProcessRecord{8d9f481 5822:com.android.bluetooth/1002}, curProc for 4679: null
11-08 11:42:19.159   929  3182 I ActivityManager: Killing 3904:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-08 11:42:19.232  5822  5822 D AdapterServiceConfig: Adding HeadsetService
,11-08 11:42:19.232  5822  5822 D AdapterServiceConfig: Adding A2dpService
11-08 11:42:19.233  5822  5822 D AdapterServiceConfig: Adding HidService
11-08 11:42:19.233  5822  5822 D AdapterServiceConfig: Adding HealthService
11-08 11:42:19.233  5822  5822 D AdapterServiceConfig: Adding PanService
11-08 11:42:19.233  5822  5822 D AdapterServiceConfig: Adding GattService
,11-08 11:42:19.233  5822  5822 D AdapterServiceConfig: Adding BluetoothMapService
11-08 11:42:19.233  5822  5822 D AdapterServiceConfig: Adding SapService
,11-08 11:42:19.244   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25f5c8c:true
,11-08 11:42:19.244  5822  5822 D BluetoothAdapterState: make() - Creating AdapterState
,11-08 11:42:19.246  5822  5822 I bt_bluedroid: init
,11-08 11:42:19.246  5822  5834 I BluetoothAdapterState: Entering OffState
,11-08 11:42:19.247  5822  5835 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-08 11:42:19.248  5822  5835 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-08 11:42:19.248  5822  5835 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-08 11:42:19.248  5822  5835 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-08 11:42:19.248  5822  5822 I bt_bluedroid: get_profile_interface socket
11-08 11:42:19.250  5822  5822 I bt_bluedroid: get_profile_interface sdp
,11-08 11:42:19.250  5822  5838 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 11:42:19.251  5822  5838 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 11:42:19.253  5822  5833 I bt_bluedroid: config_hci_snoop_log
,11-08 11:42:19.255   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-08 11:42:19.256  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 11:42:19.259  5822  5834 D BluetoothAdapterState: Current state: OFF, message: 0
11-08 11:42:19.259  5822  5834 D BluetoothAdapterProperties: Setting state to 14
11-08 11:42:19.260  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-08 11:42:19.261  5822  5834 D BluetoothBondStateMachine: make
,11-08 11:42:19.262  5822  5840 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-08 11:42:19.264  5822  5834 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:42:19.265  5822  5822 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-08 11:42:19.266  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
11-08 11:42:19.267  5822  5822 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 11:42:19.267  5822  5822 D BtGatt.GattService: Received start request. Starting profile...
11-08 11:42:19.267  5822  5822 D BtGatt.GattService: start()
11-08 11:42:19.268  5822  5822 I bt_bluedroid: get_profile_interface gatt
11-08 11:42:19.268  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
11-08 11:42:19.268  5822  5822 D BtGatt.AdvertiseManager: advertise manager created
,11-08 11:42:19.272  5822  5822 V BluetoothAdapterState: isTurningOff()=false
,11-08 11:42:19.272  5822  5822 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:19.272  5822  5822 V BluetoothAdapterState: isBleTurningOn()=true
11-08 11:42:19.272  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:19.272  5822  5834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-08 11:42:19.273  5822  5834 I bt_bluedroid: bt_bluedroid
11-08 11:42:19.273  5822  5835 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-08 11:42:19.273  5822  5835 I bt_hci  : start_up
,11-08 11:42:19.278  5822  5835 I bt_vendor: alloc value 0xf3d33871
,11-08 11:42:19.278  5822  5835 I bt_vendor: init
11-08 11:42:19.278  5822  5835 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-08 11:42:19.278  5822  5835 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-08 11:42:19.306  5789  5812 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-08 11:42:19.313   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@956948d:true
,11-08 11:42:19.385  5822  5835 D bt_hci  : start_up starting async portion
,11-08 11:42:19.385  5822  5843 I bt_hci  : event_finish_startup
11-08 11:42:19.385  5822  5843 I bt_hci_h4: hal_open
11-08 11:42:19.385  5822  5843 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-08 11:42:19.386  5822  5843 I bt_userial_vendor: device fd = 54 open
,11-08 11:42:19.383  5846  5846 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 11:42:19.398  5822  5843 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 11:42:19.401  5822  5843 D bt_hwcfg: Chipset BCM4358A3
,11-08 11:42:19.401  5822  5843 D bt_hwcfg: Target name = [BCM4358A3]
11-08 11:42:19.401  5822  5843 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-08 11:42:19.663  5822  5834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-08 11:42:19.790  5822  5843 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-08 11:42:19.791  5822  5843 D bt_hwcfg: Settlement delay -- 100 ms
,11-08 11:42:19.791  5822  5843 I bt_hwcfg: Setting fw settlement delay to 100 
,11-08 11:42:19.913  5822  5843 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 11:42:19.914  5822  5843 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-08 11:42:19.915  5822  5843 I bt_hwcfg: vendor lib fwcfg completed
,11-08 11:42:19.915  5822  5843 I bt_vendor: firmware callback
,11-08 11:42:19.916  5822  5843 I bt_hci  : firmware_config_callback
11-08 11:42:19.923  5822  5848 I bt_btu  : btu_task pending for preload complete event
11-08 11:42:19.924  5822  5848 I bt_btu_task: Bluetooth chip preload is complete
11-08 11:42:19.924  5822  5848 I bt_btu  : btu_task received preload complete event
,11-08 11:42:19.929  5822  5848 I         : BTE_InitTraceLevels -- TRC_HCI
,11-08 11:42:19.929  5822  5848 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-08 11:42:19.929  5822  5848 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-08 11:42:19.930  5822  5848 I         : BTE_InitTraceLevels -- TRC_AVDT
11-08 11:42:19.930  5822  5848 I         : BTE_InitTraceLevels -- TRC_AVRC
11-08 11:42:19.930  5822  5848 I         : BTE_InitTraceLevels -- TRC_A2D
11-08 11:42:19.930  5822  5848 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-08 11:42:19.930  5822  5848 I         : BTE_InitTraceLevels -- TRC_BTM
11-08 11:42:19.930  5822  5848 I         : BTE_InitTraceLevels -- TRC_GAP
11-08 11:42:19.930  5822  5848 I         : BTE_InitTraceLevels -- TRC_PAN
,11-08 11:42:19.930  5822  5848 I         : BTE_InitTraceLevels -- TRC_SDP
11-08 11:42:19.930  5822  5848 I         : BTE_InitTraceLevels -- TRC_GATT
11-08 11:42:19.931  5822  5848 I         : BTE_InitTraceLevels -- TRC_SMP
,11-08 11:42:19.931  5822  5848 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-08 11:42:19.931  5822  5848 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-08 11:42:20.016  5822  5848 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cb1549
11-08 11:42:20.017  5822  5848 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cb1549 
,11-08 11:42:20.038  5822  5838 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = true
,11-08 11:42:20.040  5822  5838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-08 11:42:20.040  5822  5838 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 11:42:20.042  5822  5838 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 11:42:20.045  5822  5838 D BluetoothAdapterProperties: Scan Mode:20
,11-08 11:42:20.045  5822  5838 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-08 11:42:20.046  5822  5838 D bt_hci  : do_postload posting postload work item
11-08 11:42:20.046  5822  5843 I bt_hci  : event_postload
11-08 11:42:20.046  5822  5843 I bt_vendor: sco_config_cb
11-08 11:42:20.046  5822  5843 I bt_hci  : sco_config_callback postload finished.
11-08 11:42:20.050  5822  5838 D bt_bte_conf: Device ID record 1 : primary
11-08 11:42:20.050  5822  5838 D bt_bte_conf:   vendorId            = 000f
11-08 11:42:20.050  5822  5838 D bt_bte_conf:   vendorIdSource      = 0001
11-08 11:42:20.050  5822  5838 D bt_bte_conf:   product             = 1200
11-08 11:42:20.050  5822  5838 D bt_bte_conf:   version             = 1436
11-08 11:42:20.050  5822  5838 D bt_bte_conf:   clientExecutableURL = 
11-08 11:42:20.050  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:20.050  5822  5838 D bt_bte_conf:   serviceDescription  = 
11-08 11:42:20.050  5822  5838 D bt_bte_conf:   documentationURL    = 
,11-08 11:42:20.051  5822  5838 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-08 11:42:20.051  5822  5835 D bt_stack_manager: event_start_up_stack finished
11-08 11:42:20.053  5822  5834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-08 11:42:20.056  5822  5843 I bt_vendor: low_power_mode_cb
11-08 11:42:20.057  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:20.057  5822  5834 D BluetoothAdapterProperties: Setting state to 15
,11-08 11:42:20.057  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-08 11:42:20.059  5822  5834 I BluetoothAdapterState: Entering BleOnState
11-08 11:42:20.059  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:20.061  5822  5834 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-08 11:42:20.061  5822  5834 D BluetoothAdapterProperties: Setting state to 11
11-08 11:42:20.061  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-08 11:42:20.066  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
,11-08 11:42:20.067  5822  5822 D HeadsetService: Received start request. Starting profile...
11-08 11:42:20.068  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:20.070  5822  5822 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-08 11:42:20.070  5822  5822 D HeadsetStateMachine: make
,11-08 11:42:20.070  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:20.072  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:20.083  5822  5834 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:42:20.084  5822  5822 D HeadsetStateMachine: max_hf_connections = 1
,11-08 11:42:20.084  5822  5822 I bt_bluedroid: get_profile_interface handsfree
11-08 11:42:20.084  5822  5838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-08 11:42:20.084  5822  5838 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-08 11:42:20.087  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
11-08 11:42:20.088  5822  5822 D A2dpService: Received start request. Starting profile...
11-08 11:42:20.088  5822  5822 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-08 11:42:20.089  5822  5822 I bt_bluedroid: get_profile_interface avrcp
,11-08 11:42:20.094  5822  5822 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-08 11:42:20.094  5822  5822 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-08 11:42:20.094  5822  5822 D A2dpStateMachine: make
,11-08 11:42:20.095  5822  5822 I bt_bluedroid: get_profile_interface a2dp
11-08 11:42:20.096  5822  5838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-08 11:42:20.097  5822  5855 D A2dpStateMachine: Enter Disconnected: -2
11-08 11:42:20.097  5822  5822 I BluetoothHidServiceJni: classInitNative: succeeds
,11-08 11:42:20.098  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
11-08 11:42:20.099  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 11:42:20.099  5822  5822 D HidService: Received start request. Starting profile...
11-08 11:42:20.099  5822  5822 I bt_bluedroid: get_profile_interface hidhost
,11-08 11:42:20.100  5822  5822 D HidService: setHidService(): set to: null
,11-08 11:42:20.101  5777  5777 D BluetoothInputDevice: Proxy object connected
11-08 11:42:20.101  5822  5838 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c9256d
11-08 11:42:20.101  5822  5838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-08 11:42:20.101  5777  5777 D HidProfile: Bluetooth service connected
11-08 11:42:20.101  5822  5822 I BluetoothHealthServiceJni: classInitNative: succeeds
11-08 11:42:20.102  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
11-08 11:42:20.103  5822  5822 D HealthService: Received start request. Starting profile...
,11-08 11:42:20.104  5822  5822 I bt_bluedroid: get_profile_interface health
,11-08 11:42:20.105  5822  5822 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-08 11:42:20.105  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
,11-08 11:42:20.107  5777  5777 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 11:42:20.107  5822  5822 D PanService: Received start request. Starting profile...
11-08 11:42:20.107  5777  5777 D PanProfile: Bluetooth service connected
11-08 11:42:20.107  5822  5822 D BluetoothPanServiceJni: initializeNative(L110): pan
11-08 11:42:20.107  5822  5822 I bt_bluedroid: get_profile_interface pan
,11-08 11:42:20.108  5822  5838 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-08 11:42:20.109  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
11-08 11:42:20.111  5822  5822 D BluetoothMapService: Received start request. Starting profile...
11-08 11:42:20.111  5822  5822 D BluetoothMapService: start()
11-08 11:42:20.113  5822  5822 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-08 11:42:20.114  5777  5777 D BluetoothMap: Proxy object connected
,11-08 11:42:20.114  5777  5777 D MapProfile: Bluetooth service connected
,11-08 11:42:20.114  5822  5822 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-08 11:42:20.114  5777  5777 D BluetoothMap: getConnectedDevices()
11-08 11:42:20.114  5822  5822 D BluetoothMapAppObserver: createReceiver()
11-08 11:42:20.116  5822  5822 D BluetoothMapAppObserver: initObservers()
11-08 11:42:20.116  5822  5822 D BluetoothMapAppObserver: getEnabledAccountItems()
11-08 11:42:20.116  5777  5777 D BluetoothMap: Bluetooth is Not enabled
,11-08 11:42:20.121  5822  5822 V SapService: SapBinder()
,11-08 11:42:20.121  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
11-08 11:42:20.121  5822  5822 D SapService: Received start request. Starting profile...
11-08 11:42:20.121  5822  5822 V SapService: start()
,11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.123  5822  5853 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isTurningOff()=false
,11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.123  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.124  5822  5822 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:20.124  5822  5822 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:20.124  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.124  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.124  5822  5822 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:20.124  5822  5822 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:20.124  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.124  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 11:42:20.124  5822  5822 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:20.124  5822  5822 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:20.124  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.125  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.125  5822  5822 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:20.125  5822  5822 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:20.125  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.125  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.126  5822  5834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-08 11:42:20.126  5822  5834 D BluetoothAdapterProperties: ScanMode =  20
11-08 11:42:20.126  5822  5834 D BluetoothAdapterProperties: State =  11
11-08 11:42:20.127  5822  5838 D BluetoothAdapterProperties: Scan Mode:21
11-08 11:42:20.127  5822  5838 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 11:42:20.127  5822  5834 D BluetoothAdapterProperties: Setting state to 12
11-08 11:42:20.127  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-08 11:42:20.127  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-08 11:42:20.128  5822  5834 I BluetoothAdapterState: Entering OnState
,11-08 11:42:20.128  5777  5787 D BluetoothPan: onBluetoothStateChange on: true
11-08 11:42:20.129   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-08 11:42:20.130  3146  4048 D BluetoothMap: onBluetoothStateChange: up=true
11-08 11:42:20.130  5645  5645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-08 11:42:20.130   929   929 D BluetoothA2dp: Proxy object connected
11-08 11:42:20.131   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:42:20.131  3146  3146 D BluetoothMap: Proxy object connected
11-08 11:42:20.132  3146  3146 D MapProfile: Bluetooth service connected
11-08 11:42:20.132  3146  3146 D BluetoothMap: getConnectedDevices()
11-08 11:42:20.132  3146  3172 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 11:42:20.133  5645  5645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-08 11:42:20.133  5777  5788 D BluetoothMap: onBluetoothStateChange: up=true
,11-08 11:42:20.134  5777  5787 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 11:42:20.135  3146  3146 D BluetoothA2dp: Proxy object connected
11-08 11:42:20.136   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:42:20.136  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:20.136  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:20.136  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:20.136  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:20.136  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:20.136  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:20.136  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:20.136  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:42:20.137  3146  3169 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:42:20.138  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:20.139  3816  4050 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:42:20.140  3146  3172 D BluetoothPan: onBluetoothStateChange on: true
,11-08 11:42:20.141  5822  5822 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 11:42:20.142  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:20.142  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:20.142  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:20.142  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:20.142  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:20.142  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:20.142  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:20.142  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:20.142  5822  5822 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-08 11:42:20.142   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:42:20.142  3146  3146 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 11:42:20.142  3146  3146 D PanProfile: Bluetooth service connected
11-08 11:42:20.142  3146  3169 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 11:42:20.143  5822  5822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:42:20.144  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:20.144  5777  5788 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-08 11:42:20.145  3146  3172 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-08 11:42:20.146  5822  5822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:42:20.148  3146  3146 D BluetoothInputDevice: Proxy object connected
11-08 11:42:20.148  3146  3146 D HidProfile: Bluetooth service connected
11-08 11:42:20.148   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-08 11:42:20.149  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:20.149  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:20.149  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:20.149  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:20.149  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:20.149  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:20.149  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:20.149  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:42:20.150  5822  5822 D ObexServerSockets: Succeed to create listening sockets 
11-08 11:42:20.150  5822  5822 D ObexServerSockets0: startAccept()
11-08 11:42:20.150  5822  5822 D ObexServerSockets0: prepareForNewConnect()
11-08 11:42:20.151  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:20.152  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 11:42:20.153  5777  5777 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-08 11:42:20.153  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:20.155  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:20.156  5822  5822 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-08 11:42:20.156  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:20.156  5822  5822 D BluetoothSdpJni: SDP Create record success - handle: 0
11-08 11:42:20.157  5777  5777 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-08 11:42:20.158  5822  5863 D ObexServerSockets0: Accepting socket connection...
11-08 11:42:20.158  5822  5864 D ObexServerSockets0: Accepting socket connection...
11-08 11:42:20.158  5822  5822 D BluetoothMapService: onReceive
11-08 11:42:20.158  5822  5822 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 11:42:20.158  5822  5822 D BluetoothMapService: STATE_ON
,11-08 11:42:20.161  5822  5865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:42:20.162  5822  5865 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-08 11:42:20.162  5822  5865 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-08 11:42:20.163  5777  5777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-08 11:42:20.164  5645  5707 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:20.165  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
11-08 11:42:20.165  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 11:42:20.165  5777  5777 D BluetoothA2dp: Proxy object connected
11-08 11:42:20.167  5645  5692 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-08 11:42:20.168  5645  5692 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-08 11:42:20.171  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 11:42:20.171  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:20.174  5822  5834 D BluetoothAdapterState: Current state: ON, message: 23
11-08 11:42:20.174  5822  5834 D BluetoothAdapterProperties: Setting state to 13
11-08 11:42:20.174  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-08 11:42:20.175  5822  5834 D BluetoothAdapterProperties: onBluetoothDisable()
11-08 11:42:20.175  5822  5834 I BluetoothAdapterState: Entering PendingCommandState
11-08 11:42:20.175  5777  5777 D DockEventReceiver: finishStartingService: stopping service
11-08 11:42:20.179  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:42:20.179  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:20.179  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:20.179  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:20.179  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:20.179  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:42:20.179  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:20.179  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:20.179  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:20.180  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:42:20.180  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:20.182  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 11:42:20.182  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:20.182  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:20.182  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:20.182  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:20.182  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:42:20.182  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:20.182  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:20.182  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:42:20.182  5822  5838 D BluetoothAdapterProperties: Scan Mode:20
11-08 11:42:20.182  5822  5834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-08 11:42:20.183  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:42:20.183  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:20.183  5777  5777 D BluetoothPbap: Proxy object connected
11-08 11:42:20.184  5777  5777 D PbapServerProfile: Bluetooth service connected
11-08 11:42:20.185  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:20.185  3146  3146 D BluetoothPbap: Proxy object connected
11-08 11:42:20.186  3146  3146 D PbapServerProfile: Bluetooth service connected
11-08 11:42:20.186  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:20.189  5822  5822 D BluetoothMapService: onReceive
,11-08 11:42:20.189  5822  5822 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 11:42:20.189  5822  5822 D BluetoothMapService: STATE_TURNING_OFF
11-08 11:42:20.190  5822  5822 D HeadsetService: Received stop request...Stopping profile...
,11-08 11:42:20.200  5777  5777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-08 11:42:20.205  5777  5777 D DockEventReceiver: finishStartingService: stopping service
,11-08 11:42:20.206  5822  5822 D A2dpService: Received stop request...Stopping profile...
11-08 11:42:20.206  5822  5855 D A2dpStateMachine: Exit Disconnected: -1
,11-08 11:42:20.207   929   929 D BluetoothA2dp: Proxy object disconnected
,11-08 11:42:20.208  5777  5777 D BluetoothA2dp: Proxy object disconnected
11-08 11:42:20.208  3146  3146 D BluetoothA2dp: Proxy object disconnected
,11-08 11:42:20.209  5822  5822 D HidService: Received stop request...Stopping profile...
11-08 11:42:20.209  5822  5822 D HidService: Stopping Bluetooth HidService
11-08 11:42:20.210  3146  3146 D BluetoothInputDevice: Proxy object disconnected
11-08 11:42:20.210  3146  3146 D HidProfile: Bluetooth service disconnected
11-08 11:42:20.210  5822  5822 D HealthService: Received stop request...Stopping profile...
11-08 11:42:20.210  5777  5777 D BluetoothInputDevice: Proxy object disconnected
11-08 11:42:20.211  5777  5777 D HidProfile: Bluetooth service disconnected
11-08 11:42:20.211  5822  5822 D BluetoothMapService: MAP Service closeService in
11-08 11:42:20.211  5822  5822 D BluetoothMapMasInstance0: MAP Service shutdown
11-08 11:42:20.211  5822  5822 D ObexServerSockets0: shutdown(block = true)
,11-08 11:42:20.212  5822  5863 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-08 11:42:20.212  5822  5822 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 11:42:20.212  5822  5822 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 11:42:20.212  5822  5864 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-08 11:42:20.213  5822  5850 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-08 11:42:20.214  5822  5822 D PanService: Received stop request...Stopping profile...
,11-08 11:42:20.215  3146  3146 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 11:42:20.215  3146  3146 D PanProfile: Bluetooth service disconnected
11-08 11:42:20.215  5822  5822 V BluetoothAdapterState: isTurningOff()=true
11-08 11:42:20.215  5822  5822 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:20.215  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.215  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.215  5822  5822 D BluetoothMapService: Received stop request...Stopping profile...
11-08 11:42:20.215  5822  5822 D BluetoothMapService: stop()
11-08 11:42:20.218  5822  5822 D BluetoothMapAppObserver: deinitObservers()
11-08 11:42:20.218  5822  5822 D BluetoothMapAppObserver: removeReceiver()
,11-08 11:42:20.219  5777  5777 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 11:42:20.219  5777  5777 D PanProfile: Bluetooth service disconnected
11-08 11:42:20.219  3146  3146 D BluetoothMap: Proxy object disconnected
11-08 11:42:20.219  3146  3146 D MapProfile: Bluetooth service disconnected
11-08 11:42:20.219  5777  5777 D BluetoothMap: Proxy object disconnected
11-08 11:42:20.219  5777  5777 D MapProfile: Bluetooth service disconnected
,11-08 11:42:20.220  5822  5822 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-08 11:42:20.221  5822  5822 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-08 11:42:20.221  5822  5838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-08 11:42:20.221  5822  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:42:20.221  5822  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:42:20.221  5822  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:42:20.221  5822  5838 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
11-08 11:42:20.221  5822  5822 D SapService: Received stop request...Stopping profile...
11-08 11:42:20.221  5822  5822 V SapService: stop()
11-08 11:42:20.223  5822  5822 V BluetoothAdapterState: isTurningOff()=true
11-08 11:42:20.223  5822  5822 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:20.223  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.223  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.224  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 11:42:20.225  5822  5838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-08 11:42:20.225  5822  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:42:20.225  5822  5822 V BluetoothAdapterState: isTurningOff()=true
11-08 11:42:20.225  5822  5822 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:20.225  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.225  5822  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 11:42:20.225  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.225  5822  5848 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 11:42:20.225  5822  5848 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 11:42:20.226  5822  5848 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 11:42:20.226  5822  5822 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-08 11:42:20.226  5822  5848 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 11:42:20.226  5822  5822 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-08 11:42:20.226  5822  5838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 11:42:20.226  5822  5822 V BluetoothAdapterState: isTurningOff()=true
11-08 11:42:20.226  5822  5822 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:20.226  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.226  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.226  5822  5822 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-08 11:42:20.227  5822  5838 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-08 11:42:20.227  5822  5822 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-08 11:42:20.227  5822  5822 V BluetoothAdapterState: isTurningOff()=true
,11-08 11:42:20.227  5822  5822 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:20.227  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.227  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.227  5822  5822 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-08 11:42:20.227  5822  5822 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-08 11:42:20.229  5822  5822 D BluetoothMapService: MAP Service closeService in
11-08 11:42:20.229  5822  5822 V BluetoothAdapterState: isTurningOff()=true
11-08 11:42:20.229  5822  5822 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:20.229  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.230  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.230  5822  5822 D BluetoothMapService: cleanup()
11-08 11:42:20.230  5822  5822 D BluetoothMapService: MAP Service closeService in
11-08 11:42:20.230  5822  5822 V BluetoothAdapterState: isTurningOff()=true
11-08 11:42:20.230  5822  5822 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:20.230  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.230  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.230  5822  5834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-08 11:42:20.230  5822  5834 D BluetoothAdapterProperties: Setting state to 15
11-08 11:42:20.230  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-08 11:42:20.231  5822  5834 I BluetoothAdapterState: Entering BleOnState
11-08 11:42:20.231  3146  3146 D BluetoothPbap: Proxy object disconnected
11-08 11:42:20.231  3146  3146 D PbapServerProfile: Bluetooth service disconnected
11-08 11:42:20.231  5777  5787 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-08 11:42:20.233  5777  5777 D BluetoothPbap: Proxy object disconnected
11-08 11:42:20.235  5777  5777 D PbapServerProfile: Bluetooth service disconnected
11-08 11:42:20.235  5777  5788 D BluetoothPan: onBluetoothStateChange on: false
11-08 11:42:20.236   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 11:42:20.236  3146  3169 D BluetoothMap: onBluetoothStateChange: up=false
11-08 11:42:20.237  5777  5875 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:42:20.237   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:42:20.237  3146  4048 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 11:42:20.237  5777  5787 D BluetoothMap: onBluetoothStateChange: up=false
11-08 11:42:20.238  5777  5788 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 11:42:20.239   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:42:20.239  3146  3172 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:42:20.239  3816  4332 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:42:20.239  3146  3169 D BluetoothPan: onBluetoothStateChange on: false
11-08 11:42:20.240   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 11:42:20.240  3146  4048 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 11:42:20.240  5777  5875 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 11:42:20.241  3146  3172 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 11:42:20.241  5822  5834 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-08 11:42:20.241  5822  5834 D BluetoothAdapterProperties: Setting state to 16
11-08 11:42:20.241  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-08 11:42:20.242  5822  5834 D BluetoothAdapterProperties: onBleDisable
11-08 11:42:20.242  5822  5834 I BluetoothAdapterState: Entering PendingCommandState
11-08 11:42:20.243  5822  5835 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-08 11:42:20.244  5822  5838 D BluetoothAdapterProperties: Scan Mode:20
11-08 11:42:20.244  5777  5777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 11:42:20.245  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:20.246  5822  5848 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-08 11:42:20.246  5822  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-08 11:42:20.248  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:20.250  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:20.251  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 11:42:20.252  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:20.254  5777  5777 D DockEventReceiver: finishStartingService: stopping service
,11-08 11:42:20.445  5822  5838 I bt_hci  : shut_down
11-08 11:42:20.446  5822  5843 D bt_hwcfg: hw_epilog_process
,11-08 11:42:20.446  5822  5843 I bt_vendor: low_power_mode_cb
,11-08 11:42:20.449  5822  5843 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-08 11:42:20.449  5822  5843 I bt_vendor: epilog_cb
11-08 11:42:20.449  5822  5843 I bt_hci  : epilog_finished_callback
,11-08 11:42:20.450  5822  5838 I bt_hci_h4: hal_close
11-08 11:42:20.450  5822  5838 I bt_userial_vendor: device fd = 54 close
,11-08 11:42:20.574  5822  5835 D bt_stack_manager: event_shut_down_stack finished.
,11-08 11:42:20.574  5822  5834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-08 11:42:20.579  5822  5834 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-08 11:42:20.579  5822  5822 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 11:42:20.580  5822  5822 D BtGatt.GattService: Received stop request...Stopping profile...
11-08 11:42:20.580  5822  5822 D BtGatt.GattService: stop()
11-08 11:42:20.581  5822  5822 D BtGatt.AdvertiseManager: advertise clients cleared
,11-08 11:42:20.584  5822  5822 V BluetoothAdapterState: isTurningOff()=false
,11-08 11:42:20.584  5822  5822 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:20.585  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:20.585  5822  5822 V BluetoothAdapterState: isBleTurningOff()=true
,11-08 11:42:20.585  5822  5834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-08 11:42:20.586  5822  5834 D BluetoothAdapterProperties: Setting state to 10
11-08 11:42:20.586  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-08 11:42:20.587  5822  5834 I BluetoothAdapterState: Entering OffState
11-08 11:42:20.588   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-08 11:42:20.600  5822  5822 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-08 11:42:20.600  5822  5822 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-08 11:42:20.600  5822  5822 I BluetoothServiceJni: cleanupNative: return from cleanup
11-08 11:42:20.603  5822  5835 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-08 11:42:20.609  5822  5822 I art     : System.exit called, status: 0
,11-08 11:42:20.610  5822  5822 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-08 11:42:20.642   929  3846 I ActivityManager: Process com.android.bluetooth (pid 5822) has died
,11-08 11:42:20.675  5645  5707 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 11:42:20.675  5645  5707 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:20.675  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:20.675  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:20.675  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:20.675  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 11:42:20.675  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:20.675  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:20.675  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:42:20.675  5645  5707 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 11:42:20.676  5645  5707 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:20.676  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:20.692   929   946 I ActivityManager: Start proc 5878:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-08 11:42:20.750  5878  5878 D AdapterServiceConfig: Adding HeadsetService
,11-08 11:42:20.750  5878  5878 D AdapterServiceConfig: Adding A2dpService
11-08 11:42:20.751  5878  5878 D AdapterServiceConfig: Adding HidService
11-08 11:42:20.751  5878  5878 D AdapterServiceConfig: Adding HealthService
11-08 11:42:20.751  5878  5878 D AdapterServiceConfig: Adding PanService
11-08 11:42:20.751  5878  5878 D AdapterServiceConfig: Adding GattService
11-08 11:42:20.751  5878  5878 D AdapterServiceConfig: Adding BluetoothMapService
11-08 11:42:20.751  5878  5878 D AdapterServiceConfig: Adding SapService
,11-08 11:42:20.763   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c021e4:true
,11-08 11:42:20.763  5878  5878 D BluetoothAdapterState: make() - Creating AdapterState
,11-08 11:42:20.766  5878  5878 I bt_bluedroid: init
,11-08 11:42:20.766  5878  5890 I BluetoothAdapterState: Entering OffState
,11-08 11:42:20.768  5878  5891 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-08 11:42:20.768  5878  5891 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-08 11:42:20.768  5878  5891 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-08 11:42:20.768  5878  5891 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-08 11:42:20.769  5878  5878 I bt_bluedroid: get_profile_interface socket
,11-08 11:42:20.770  5878  5894 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 11:42:20.771  5878  5878 I bt_bluedroid: get_profile_interface sdp
11-08 11:42:20.773  5878  5894 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 11:42:20.776  5878  5889 I bt_bluedroid: config_hci_snoop_log
11-08 11:42:20.777   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-08 11:42:20.780  5878  5890 D BluetoothAdapterState: Current state: OFF, message: 0
,11-08 11:42:20.780  5878  5890 D BluetoothAdapterProperties: Setting state to 14
11-08 11:42:20.781  5878  5890 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-08 11:42:20.782  5878  5890 D BluetoothBondStateMachine: make
11-08 11:42:20.783  5878  5895 I BluetoothBondStateMachine: StableState(): Entering Off State
11-08 11:42:20.786  5878  5890 I BluetoothAdapterState: Entering PendingCommandState
11-08 11:42:20.786  5878  5878 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-08 11:42:20.788  5878  5878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
,11-08 11:42:20.789  5878  5878 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-08 11:42:20.789  5878  5878 D BtGatt.GattService: Received start request. Starting profile...
11-08 11:42:20.789  5878  5878 D BtGatt.GattService: start()
11-08 11:42:20.789  5878  5878 I bt_bluedroid: get_profile_interface gatt
11-08 11:42:20.791  5878  5878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
11-08 11:42:20.791  5878  5878 D BtGatt.AdvertiseManager: advertise manager created
,11-08 11:42:20.795  5878  5878 V BluetoothAdapterState: isTurningOff()=false
,11-08 11:42:20.795  5878  5878 V BluetoothAdapterState: isTurningOn()=false
11-08 11:42:20.795  5878  5878 V BluetoothAdapterState: isBleTurningOn()=true
11-08 11:42:20.795  5878  5878 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:20.796  5878  5890 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-08 11:42:20.797  5878  5890 I bt_bluedroid: bt_bluedroid
11-08 11:42:20.797  5878  5891 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-08 11:42:20.797  5878  5891 I bt_hci  : start_up
,11-08 11:42:20.802  5878  5891 I bt_vendor: alloc value 0xf3d33871
11-08 11:42:20.802  5878  5891 I bt_vendor: init
,11-08 11:42:20.802  5878  5891 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-08 11:42:20.802  5878  5891 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-08 11:42:20.912  5878  5891 D bt_hci  : start_up starting async portion
,11-08 11:42:20.912  5878  5898 I bt_hci  : event_finish_startup
11-08 11:42:20.912  5878  5898 I bt_hci_h4: hal_open
11-08 11:42:20.913  5878  5898 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-08 11:42:20.915  5878  5898 I bt_userial_vendor: device fd = 54 open
,11-08 11:42:20.910  5899  5899 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 11:42:20.929  5878  5898 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 11:42:20.932  5878  5898 D bt_hwcfg: Chipset BCM4358A3
,11-08 11:42:20.932  5878  5898 D bt_hwcfg: Target name = [BCM4358A3]
11-08 11:42:20.933  5878  5898 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-08 11:42:21.184  5878  5890 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-08 11:42:21.326  5878  5898 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-08 11:42:21.326  5878  5898 D bt_hwcfg: Settlement delay -- 100 ms
,11-08 11:42:21.326  5878  5898 I bt_hwcfg: Setting fw settlement delay to 100 
,11-08 11:42:21.449  5878  5898 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 11:42:21.449  5878  5898 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-08 11:42:21.451  5878  5898 I bt_hwcfg: vendor lib fwcfg completed
,11-08 11:42:21.451  5878  5898 I bt_vendor: firmware callback
,11-08 11:42:21.451  5878  5898 I bt_hci  : firmware_config_callback
,11-08 11:42:21.459  5878  5901 I bt_btu  : btu_task pending for preload complete event
,11-08 11:42:21.460  5878  5901 I bt_btu_task: Bluetooth chip preload is complete
,11-08 11:42:21.460  5878  5901 I bt_btu  : btu_task received preload complete event
,11-08 11:42:21.467  5878  5901 I         : BTE_InitTraceLevels -- TRC_HCI
,11-08 11:42:21.467  5878  5901 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-08 11:42:21.468  5878  5901 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-08 11:42:21.468  5878  5901 I         : BTE_InitTraceLevels -- TRC_AVDT
11-08 11:42:21.468  5878  5901 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-08 11:42:21.469  5878  5901 I         : BTE_InitTraceLevels -- TRC_A2D
11-08 11:42:21.469  5878  5901 I         : BTE_InitTraceLevels -- TRC_BNEP
11-08 11:42:21.469  5878  5901 I         : BTE_InitTraceLevels -- TRC_BTM
11-08 11:42:21.469  5878  5901 I         : BTE_InitTraceLevels -- TRC_GAP
,11-08 11:42:21.469  5878  5901 I         : BTE_InitTraceLevels -- TRC_PAN
11-08 11:42:21.469  5878  5901 I         : BTE_InitTraceLevels -- TRC_SDP
11-08 11:42:21.469  5878  5901 I         : BTE_InitTraceLevels -- TRC_GATT
11-08 11:42:21.469  5878  5901 I         : BTE_InitTraceLevels -- TRC_SMP
11-08 11:42:21.469  5878  5901 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-08 11:42:21.469  5878  5901 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-08 11:42:21.551  5878  5901 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cb1549
,11-08 11:42:21.551  5878  5901 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cb1549 
,11-08 11:42:21.567  5773  5773 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 11:42:21.571  5773  5773 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 11:42:21.574  5773  5773 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-08 11:42:21.576  5878  5894 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-08 11:42:21.578  5773  5773 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 11:42:21.578  5878  5894 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 11:42:21.579  5878  5894 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 11:42:21.582  5878  5894 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 11:42:21.585  5878  5894 D BluetoothAdapterProperties: Scan Mode:20
11-08 11:42:21.586  5878  5894 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 11:42:21.586  5878  5894 D bt_hci  : do_postload posting postload work item
11-08 11:42:21.586  5878  5898 I bt_hci  : event_postload
11-08 11:42:21.586  5878  5898 I bt_vendor: sco_config_cb
11-08 11:42:21.586  5878  5898 I bt_hci  : sco_config_callback postload finished.
11-08 11:42:21.588  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:21.589  5878  5894 D bt_bte_conf: Device ID record 1 : primary
11-08 11:42:21.589  5878  5894 D bt_bte_conf:   vendorId            = 000f
11-08 11:42:21.589  5878  5894 D bt_bte_conf:   vendorIdSource      = 0001
11-08 11:42:21.589  5878  5894 D bt_bte_conf:   product             = 1200
11-08 11:42:21.589  5878  5894 D bt_bte_conf:   version             = 1436
11-08 11:42:21.589  5878  5894 D bt_bte_conf:   clientExecutableURL = 
11-08 11:42:21.589  5878  5894 D bt_bte_conf:   serviceDescription  = 
11-08 11:42:21.589  5878  5894 D bt_bte_conf:   documentationURL    = 
11-08 11:42:21.590  5878  5894 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-08 11:42:21.590  5878  5891 D bt_stack_manager: event_start_up_stack finished
,11-08 11:42:21.590  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:21.590  5878  5890 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-08 11:42:21.590  5878  5890 D BluetoothAdapterProperties: Setting state to 15
11-08 11:42:21.590  5878  5890 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-08 11:42:21.591  5878  5890 I BluetoothAdapterState: Entering BleOnState
,11-08 11:42:21.594  5878  5890 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-08 11:42:21.594  5878  5890 D BluetoothAdapterProperties: Setting state to 11
,11-08 11:42:21.594  5878  5890 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-08 11:42:21.599  5878  5898 I bt_vendor: low_power_mode_cb
11-08 11:42:21.600  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:21.601  5878  5878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
,11-08 11:42:21.603  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:21.603   929   929 D BluetoothHeadset: Proxy object connected
,11-08 11:42:21.604  3146  4048 D BluetoothHeadset: Proxy object connected
,11-08 11:42:21.604   929   929 D BluetoothHeadset: Proxy object connected
11-08 11:42:21.605  5777  5788 D BluetoothHeadset: Proxy object connected
11-08 11:42:21.606  3146  3146 D HeadsetProfile: Bluetooth service connected
11-08 11:42:21.606  3816  3848 D BluetoothHeadset: Proxy object connected
,11-08 11:42:21.606  5878  5878 D HeadsetService: Received start request. Starting profile...
11-08 11:42:21.607   929   929 D BluetoothHeadset: Proxy object connected
11-08 11:42:21.610  5878  5878 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-08 11:42:21.610  5878  5878 D HeadsetStateMachine: make
11-08 11:42:21.612  5878  5890 I BluetoothAdapterState: Entering PendingCommandState
,11-08 11:42:21.618  5878  5878 D HeadsetStateMachine: max_hf_connections = 1
,11-08 11:42:21.618  5878  5878 I bt_bluedroid: get_profile_interface handsfree
11-08 11:42:21.618  5878  5894 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-08 11:42:21.618  5878  5894 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-08 11:42:21.622  5878  5878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
,11-08 11:42:21.622  5878  5878 D A2dpService: Received start request. Starting profile...
11-08 11:42:21.623  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 11:42:21.623  5878  5878 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-08 11:42:21.623  5878  5878 I bt_bluedroid: get_profile_interface avrcp
,11-08 11:42:21.630  5878  5878 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-08 11:42:21.630  5878  5878 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-08 11:42:21.630  5878  5878 D A2dpStateMachine: make
,11-08 11:42:21.608  5777  5777 D HeadsetProfile: Bluetooth service connected
,11-08 11:42:21.631  5878  5878 I bt_bluedroid: get_profile_interface a2dp
,11-08 11:42:21.631   929  2985 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-08 11:42:21.632  5878  5894 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-08 11:42:21.633   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-08 11:42:21.633   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-08 11:42:21.633  5878  5910 D A2dpStateMachine: Enter Disconnected: -2
11-08 11:42:21.634  5878  5878 I BluetoothHidServiceJni: classInitNative: succeeds
11-08 11:42:21.634  5878  5878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
,11-08 11:42:21.635  5878  5878 D HidService: Received start request. Starting profile...
11-08 11:42:21.635  5878  5878 I bt_bluedroid: get_profile_interface hidhost
11-08 11:42:21.635  5878  5878 D HidService: setHidService(): set to: null
11-08 11:42:21.635  5878  5894 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c9256d
11-08 11:42:21.636  5878  5878 I BluetoothHealthServiceJni: classInitNative: succeeds
11-08 11:42:21.636  5878  5894 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-08 11:42:21.636  5878  5878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
11-08 11:42:21.637  5878  5878 D HealthService: Received start request. Starting profile...
,11-08 11:42:21.638  5878  5878 I bt_bluedroid: get_profile_interface health
,11-08 11:42:21.639  5878  5878 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-08 11:42:21.639  5878  5878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
,11-08 11:42:21.640  5878  5878 D PanService: Received start request. Starting profile...
11-08 11:42:21.640  5878  5878 D BluetoothPanServiceJni: initializeNative(L110): pan
11-08 11:42:21.640  5878  5878 I bt_bluedroid: get_profile_interface pan
11-08 11:42:21.641  5878  5894 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-08 11:42:21.642  5878  5878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
,11-08 11:42:21.643  5878  5878 D BluetoothMapService: Received start request. Starting profile...
11-08 11:42:21.643  5878  5878 D BluetoothMapService: start()
11-08 11:42:21.644   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
11-08 11:42:21.645  5878  5878 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-08 11:42:21.646  5878  5878 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-08 11:42:21.646  5878  5878 D BluetoothMapAppObserver: createReceiver()
11-08 11:42:21.647  5878  5878 D BluetoothMapAppObserver: initObservers()
11-08 11:42:21.647  5878  5878 D BluetoothMapAppObserver: getEnabledAccountItems()
11-08 11:42:21.652  5878  5878 V SapService: SapBinder()
11-08 11:42:21.652  5878  5878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
11-08 11:42:21.653  5878  5878 D SapService: Received start request. Starting profile...
11-08 11:42:21.653  5878  5878 V SapService: start()
11-08 11:42:21.655  5878  5878 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:21.655  5878  5878 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:21.655  5878  5908 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-08 11:42:21.655  5878  5878 V BluetoothAdapterState: isBleTurningOn()=false
,11-08 11:42:21.656  5878  5878 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:21.656  5878  5878 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:21.656  5878  5878 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:21.656  5878  5878 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:21.656  5878  5878 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:21.657  5878  5878 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:21.657  5878  5878 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:21.657  5878  5878 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:21.657  5878  5878 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:21.657  5878  5878 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:21.657  5878  5878 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:21.657  5878  5878 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:21.657  5878  5878 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 11:42:21.657  5878  5878 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:21.657  5878  5878 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:21.658  5878  5878 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:21.658  5878  5878 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:21.658  5878  5878 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:21.658  5878  5878 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:21.658  5878  5878 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:21.658  5878  5878 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:21.659  5878  5878 V BluetoothAdapterState: isTurningOff()=false
11-08 11:42:21.659  5878  5878 V BluetoothAdapterState: isTurningOn()=true
11-08 11:42:21.659  5878  5878 V BluetoothAdapterState: isBleTurningOn()=false
11-08 11:42:21.659  5878  5878 V BluetoothAdapterState: isBleTurningOff()=false
11-08 11:42:21.660  5878  5890 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-08 11:42:21.660  5878  5890 D BluetoothAdapterProperties: ScanMode =  20
11-08 11:42:21.660  5878  5890 D BluetoothAdapterProperties: State =  11
,11-08 11:42:21.661  5878  5894 D BluetoothAdapterProperties: Scan Mode:21
,11-08 11:42:21.661  5878  5894 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 11:42:21.662  5878  5890 D BluetoothAdapterProperties: Setting state to 12
11-08 11:42:21.662  5878  5890 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-08 11:42:21.662  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 11:42:21.662  5777  5875 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 11:42:21.662  5878  5890 I BluetoothAdapterState: Entering OnState
11-08 11:42:21.665  5777  5787 D BluetoothPan: onBluetoothStateChange on: true
11-08 11:42:21.666   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 11:42:21.667  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:21.667  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:21.667  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:21.667  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:21.667  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:21.667  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:21.667  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:21.667  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:42:21.667  3146  3172 D BluetoothMap: onBluetoothStateChange: up=true
11-08 11:42:21.667   929   929 D BluetoothA2dp: Proxy object connected
,11-08 11:42:21.668  5777  5777 D BluetoothA2dp: Proxy object connected
,11-08 11:42:21.669  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:21.671  5777  5875 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-08 11:42:21.671  3146  3146 D BluetoothMap: Proxy object connected
11-08 11:42:21.671  3146  3146 D MapProfile: Bluetooth service connected
11-08 11:42:21.671  3146  3146 D BluetoothMap: getConnectedDevices()
11-08 11:42:21.671   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:42:21.672  3146  4048 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 11:42:21.672  5878  5878 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 11:42:21.672  5878  5878 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-08 11:42:21.673  3146  3146 D BluetoothA2dp: Proxy object connected
11-08 11:42:21.673  5777  5787 D BluetoothMap: onBluetoothStateChange: up=true
11-08 11:42:21.673  5777  5777 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 11:42:21.674  5777  5777 D PanProfile: Bluetooth service connected
11-08 11:42:21.674  5878  5878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:42:21.674  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:21.674  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:21.674  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:21.674  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:21.674  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:21.674  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:21.674  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:21.674  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:42:21.676  5777  5875 D BluetoothPbap: onBluetoothStateChange: up=true
,11-08 11:42:21.676  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:21.677  5878  5878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:42:21.677  5777  5777 D BluetoothMap: Proxy object connected
11-08 11:42:21.678  5777  5777 D MapProfile: Bluetooth service connected
11-08 11:42:21.678  5777  5777 D BluetoothMap: getConnectedDevices()
11-08 11:42:21.678  5878  5878 D ObexServerSockets: Succeed to create listening sockets 
11-08 11:42:21.678   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:42:21.678  5878  5878 D ObexServerSockets0: startAccept()
11-08 11:42:21.678  5878  5878 D ObexServerSockets0: prepareForNewConnect()
11-08 11:42:21.678  3146  3169 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:42:21.679  3816  4332 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-08 11:42:21.679  3146  3172 D BluetoothPan: onBluetoothStateChange on: true
,11-08 11:42:21.680   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
11-08 11:42:21.681  5878  5916 D ObexServerSockets0: Accepting socket connection...
11-08 11:42:21.681  5878  5878 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-08 11:42:21.681  3146  3146 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 11:42:21.681   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 11:42:21.681  5878  5878 D BluetoothSdpJni: SDP Create record success - handle: 0
11-08 11:42:21.681  3146  3146 D PanProfile: Bluetooth service connected
11-08 11:42:21.681  3146  3169 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 11:42:21.682  5878  5917 D ObexServerSockets0: Accepting socket connection...
,11-08 11:42:21.683  5777  5787 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 11:42:21.685  3146  4048 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-08 11:42:21.685  5773  5773 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
11-08 11:42:21.686  3146  3146 D BluetoothInputDevice: Proxy object connected
11-08 11:42:21.686  3146  3146 D HidProfile: Bluetooth service connected
11-08 11:42:21.687  5777  5777 D BluetoothInputDevice: Proxy object connected
11-08 11:42:21.687  5777  5777 D HidProfile: Bluetooth service connected
11-08 11:42:21.688  5878  5878 D BluetoothMapService: onReceive
11-08 11:42:21.688  5878  5878 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 11:42:21.688  5645  5707 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:21.688  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:21.688  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:21.688  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:21.688  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:21.688  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:21.688  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:21.688  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 11:42:21.688  5878  5878 D BluetoothMapService: STATE_ON
11-08 11:42:21.688  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 11:42:21.688   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-08 11:42:21.688   929   929 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,11-08 11:42:21.691  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:21.692  5645  5707 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:21.693  5645  5692 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-08 11:42:21.694   929  3138 D WifiService: setWifiEnabled: false pid=5645, uid=10077
11-08 11:42:21.694  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:21.694   929  3138 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 11:42:21.695  5777  5777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 11:42:21.695  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:21.697  5878  5920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:42:21.700  5878  5920 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-08 11:42:21.700  5878  5920 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-08 11:42:21.702  5777  5777 D DockEventReceiver: finishStartingService: stopping service
,11-08 11:42:21.703  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 11:42:21.705   929   929 D RttService: SCAN_AVAILABLE : 1
11-08 11:42:21.705   929  3094 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 11:42:21.712   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 11:42:21.712  5777  5777 D BluetoothPbap: Proxy object connected
11-08 11:42:21.712   509   927 D CommandListener: Clearing all IP addresses on wlan0
11-08 11:42:21.713  5777  5777 D PbapServerProfile: Bluetooth service connected
,11-08 11:42:21.716   929  2985 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 11:42:21.717  5773  5773 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-08 11:42:21.720  3146  3146 D BluetoothPbap: Proxy object connected
,11-08 11:42:21.720  3146  3146 D PbapServerProfile: Bluetooth service connected
,11-08 11:42:21.723  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:21.723  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:21.723  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:21.723  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:42:21.723  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:21.723  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:21.723  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:21.723  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:21.724  5878  5878 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-08 11:42:21.725  5878  5878 D ObexServerSockets0: prepareForNewConnect()
11-08 11:42:21.725  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:21.727  5773  5773 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-08 11:42:21.729  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:21.729  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:21.729  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:21.729  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:42:21.729  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:21.729  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:21.729  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:21.729  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:21.730  5878  5925 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:42:21.731  5773  5773 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,11-08 11:42:21.732  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:21.744  5878  5929 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:42:21.745  5878  5929 I BtOppRfcommListener: Accept thread started.
,11-08 11:42:21.747  5773  5773 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-08 11:42:21.755  5773  5773 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-08 11:42:21.760   929  2985 D wifi    : In wifi stop Hal
,11-08 11:42:21.760  4506  4506 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 11:42:21.760   929  2985 D wifi    : halHandle = 0x7f61dce080, mVM = 0x7f7e44d140, mCls = 0x2014d2
11-08 11:42:21.760   929  5772 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-08 11:42:21.760   929  5772 D WifiHAL : Got a signal to exit!!!
11-08 11:42:21.760   929  5772 I WifiHAL : Exit wifi_event_loop
11-08 11:42:21.760   929  2985 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-08 11:42:21.761   929  2985 E WifiHAL : Event processing terminated
11-08 11:42:21.761   929  2985 D wifi    : In wifi cleaned up handler
11-08 11:42:21.761   929  2985 I WifiHAL : Internal cleanup completed
11-08 11:42:21.762  3755  4220 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 11:42:21.762  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:21.764  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:21.789   929  5772 D wifi    : set interface wlan0 flags (DOWN)
,11-08 11:42:21.789   929  2985 D WifiNative-HAL: HAL event thread stopped successfully
,11-08 11:42:21.995   929   946 D Tethering: InitialState.processMessage what=4
,11-08 11:42:22.002   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-08 11:42:22.204  5645  5707 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:22.204  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:22.204  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:22.204  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 11:42:22.204  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:22.204  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:22.204  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:22.204  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:22.210  5645  5707 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:22.213   929  3449 D WifiService: setWifiEnabled: true pid=5645, uid=10077
,11-08 11:42:22.214   929  3449 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 11:42:22.215  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:22.224   509   927 D SoftapController: Softap fwReload - Ok
,11-08 11:42:22.229   509   927 D CommandListener: Setting iface cfg
,11-08 11:42:22.229   509   927 D CommandListener: Trying to bring down wlan0
,11-08 11:42:22.230   509   927 D CommandListener: Clearing all IP addresses on wlan0
,11-08 11:42:22.235   929  2985 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 11:42:22.724   929  3836 D WifiService: setWifiEnabled: true pid=5645, uid=10077
,11-08 11:42:22.728   929  3836 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:42:22.818   929  2985 D wifi    : set interface wlan0 flags (UP)
,11-08 11:42:22.819   929  2985 I WifiHAL : Initializing wifi
,11-08 11:42:22.819   929  2985 I WifiHAL : Creating socket
,11-08 11:42:22.825   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-08 11:42:22.827   929  2985 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-08 11:42:22.827   929  2985 D wifi    : Did set static halHandle = 0x7f61dce080
11-08 11:42:22.827   929  2985 D wifi    : halHandle = 0x7f61dce080, mVM = 0x7f7e44d140, mCls = 0x10133a
,11-08 11:42:22.828   929  2985 D wifi    : array field set
11-08 11:42:22.830   929  2985 I WifiNative-HAL: interface[0] = wlan0
,11-08 11:42:22.835   929  5932 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547102711936
11-08 11:42:22.835   929  5932 D wifi    : waitForHalEvents called, vm = 0x7f7e44d140, obj = 0x10133a, env = 0x7f61e3fb80
,11-08 11:42:22.883  5933  5933 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-08 11:42:22.936   929  2985 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-08 11:42:22.943  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:22.947  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:22.951  5933  5933 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 11:42:22.977  5933  5933 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-08 11:42:22.977  5933  5933 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-08 11:42:22.989   929  2985 D WifiConfigStore: Loading config and enabling all networks 
,11-08 11:42:22.998  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:22.998  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:22.998  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:22.998  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:22.998  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:22.998  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:22.998  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:22.998  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:23.000  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:23.003  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:23.003  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:23.003  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:23.003  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:23.003  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:23.003  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:23.003  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:23.003  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:23.006  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 11:42:23.008   929  2985 D WifiConfigStore: loaded 0 passpoint configs
,11-08 11:42:23.009   929  2985 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-08 11:42:23.009   929  2985 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-08 11:42:23.009   929  2985 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-08 11:42:23.010   929  2985 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-08 11:42:23.010   929  2985 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-08 11:42:23.011   929  2985 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-08 11:42:23.011   929  2985 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-08 11:42:23.011   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-08 11:42:23.011   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-08 11:42:23.011   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-08 11:42:23.011   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-08 11:42:23.011   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-08 11:42:23.013   929  2985 D WifiNative-HAL: Setting external_sim to 1
,11-08 11:42:23.014   929  2985 D wifi    : setting dfs flag to true, 0x7f6717d620
11-08 11:42:23.014  4506  4506 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 11:42:23.014   929  2985 D WifiStateMachine: Setting OUI to DA-A1-19
11-08 11:42:23.014   929  2985 D wifi    : setting scan oui 0x7f6717d620
11-08 11:42:23.014   929  2985 D WifiHAL : Sending mac address OUI
,11-08 11:42:23.017   929  2985 E native  : do suspend false
,11-08 11:42:23.024   929  2985 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-08 11:42:23.024   929   929 D RttService: SCAN_AVAILABLE : 3
11-08 11:42:23.024   929  3094 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 11:42:23.028   509   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-08 11:42:23.029   509   927 D CommandListener: Setting iface cfg
,11-08 11:42:23.030   929  2984 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
11-08 11:42:23.030   929  2984 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-08 11:42:23.034   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=110578 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=5 mControllerEnergyUsed=19 }
,11-08 11:42:23.035   929  2984 D WifiNative-HAL: p2pGetDeviceAddress
11-08 11:42:23.035   929  2984 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-08 11:42:23.240  5645  5707 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:23.240  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:23.240  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:23.240  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:23.240  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:23.240  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:23.240  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:23.240  5645  5707 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:23.245  5645  5707 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:23.250  5645  5692 D BluetoothAdapter: enable(): BT is already enabled..!
11-08 11:42:23.251   929  3858 D WifiService: setWifiEnabled: true pid=5645, uid=10077
11-08 11:42:23.251   929  3858 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 11:42:23.253  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-08 11:42:23.253  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 11:42:23.253  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 11:42:23.253  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-08 11:42:23.253  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-08 11:42:23.254  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8919e35 removed from the list
11-08 11:42:23.254  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-08 11:42:23.254  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@632b2ca removed from the list
,11-08 11:42:23.254  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
11-08 11:42:23.254  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 11:42:23.255  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 11:42:23.260  5645  5692 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-08 11:42:23.262  5645  5692 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-08 11:42:23.265  5645  5692 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-08 11:42:23.267  5645  5692 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-08 11:42:23.269  5645  5692 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-08 11:42:23.271  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-08 11:42:23.272  5645  5692 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-08 11:42:23.273  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-08 11:42:23.275  5645  5692 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-08 11:42:23.278  5645  5692 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-08 11:42:23.278  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6a11030 Bundle[{}]
,11-08 11:42:23.280  5645  5692 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,11-08 11:42:23.281  5645  5692 I io.jxcore.node.LifeCycleMonitor: start: OK
11-08 11:42:23.281  5645  5692 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-08 11:42:23.283  5645  5692 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-08 11:42:23.284  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-08 11:42:23.284  5645  5692 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-08 11:42:23.284  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-08 11:42:23.285  5645  5692 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-08 11:42:23.285  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-08 11:42:23.286  5645  5692 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-08 11:42:23.287  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-08 11:42:23.290  5645  5692 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-08 11:42:23.292  5645  5692 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-08 11:42:23.293  5645  5692 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-08 11:42:23.294  5645  5692 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-08 11:42:23.294  5645  5692 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-08 11:42:23.295  5645  5692 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-08 11:42:23.297  5645  5692 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-08 11:42:23.298  5645  5692 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-08 11:42:23.299  5645  5692 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-08 11:42:23.301  5645  5692 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-08 11:42:23.302  5645  5692 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-08 11:42:23.303  5645  5692 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-08 11:42:23.303  5645  5692 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
,11-08 11:42:23.304  5645  5692 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,11-08 11:42:23.305  5645  5692 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-08 11:42:23.305  5645  5692 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
,11-08 11:42:23.306  5645  5692 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-08 11:42:23.307  5645  5692 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-08 11:42:23.308  5645  5692 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-08 11:42:23.309  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-08 11:42:23.309  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cae8b1 added. We now have 3 listener(s)
,11-08 11:42:23.311  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 11:42:23.311  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 11:42:23.311  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 11:42:23.311  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 11:42:23.311  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3313196 added. We now have 3 listener(s)
11-08 11:42:23.311  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-08 11:42:23.312  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 11:42:23.315  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 11:42:23.319  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 11:42:23.319  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:23.319  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:23.319  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:23.319  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:23.319  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 11:42:23.319  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 11:42:23.319  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 11:42:23.321  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 11:42:23.321  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 11:42:23.323  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 11:42:23.324  5645  5692 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-08 11:42:23.324  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 11:42:23.325  5645  5692 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-08 11:42:23.325  5645  5692 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-08 11:42:23.325  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-08 11:42:23.326  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 11:42:23.326  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 11:42:23.326  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-08 11:42:23.326  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:42:23.327  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 11:42:23.327  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 11:42:23.327  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 11:42:23.327  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 11:42:23.327  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 11:42:23.328  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 11:42:23.328  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:42:23.328  5645  5935 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 11:42:23.328  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-08 11:42:23.328  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 11:42:23.328  5645  5935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 11:42:23.331  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 11:42:23.330  5918  5918 W Binder_6: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33310]" dev="sockfs" ino=33310 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 11:42:23.331  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 11:42:23.332  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 11:42:23.333  5645  5935 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 11:42:23.330  5918  5918 W Binder_6: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33310]" dev="sockfs" ino=33310 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 11:42:23.336  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 11:42:23.337  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 11:42:23.337  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 11:42:23.339  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:23.339  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:42:23.339  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:42:23.339  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-08 11:42:23.339  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:42:23.339  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:23.339  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:23.339  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:23.339  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:23.341  5645  5692 D BluetoothAdapter: STATE_ON
,11-08 11:42:23.344  5878  5915 D BtGatt.GattService: registerClient() - UUID=7fbcbc6d-bc41-470d-b983-f8f3f1856e9c
,11-08 11:42:23.345  5878  5894 D BtGatt.GattService: onClientRegistered() - UUID=7fbcbc6d-bc41-470d-b983-f8f3f1856e9c, clientIf=5
,11-08 11:42:23.345  5645  5656 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 11:42:23.347  5878  5896 D BtGatt.AdvertiseManager: message : 0
,11-08 11:42:23.350  5878  5896 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 11:42:23.353  5878  5894 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 11:42:23.355  5878  5894 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 11:42:23.356  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:23.356  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:23.356  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-08 11:42:23.356  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:23.356  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:23.356  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:23.356  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:23.356  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:23.356  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 11:42:23.357  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:42:23.357  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:23.360  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:23.360  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:23.360  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:23.360  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-08 11:42:23.360  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 11:42:23.360  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:23.361  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:42:23.361  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 11:42:23.361  5645  5645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:23.361  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 11:42:23.361  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 11:42:23.361  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 11:42:23.361  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-08 11:42:23.361  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 11:42:23.361  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 11:42:23.361  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 11:42:23.364  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 11:42:23.364  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 11:42:23.364  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 11:42:23.364  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 11:42:23.364  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:42:23.364  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:23.364  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 11:42:23.865  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-08 11:42:23.865  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 11:42:23.865  5645  5645 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 11:42:26.862  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-08 11:42:26.862  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 11:42:26.863  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 11:42:26.863  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 11:42:26.863  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 11:42:26.863  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-08 11:42:26.863  5645  5935 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 11:42:26.864  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 11:42:26.864  5645  5935 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-08 11:42:26.864  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 11:42:26.864  5645  5935 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 11:42:26.864  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-08 11:42:26.864  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:42:26.864  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 11:42:26.864  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 11:42:26.864  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:42:26.865  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 11:42:26.865  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 11:42:26.865  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:26.865  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.869  5645  5692 D BluetoothAdapter: STATE_ON
11-08 11:42:26.870  5645  5692 D BluetoothLeScanner: could not find callback wrapper
11-08 11:42:26.870  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 11:42:26.870  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:26.870  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.870  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 11:42:26.871  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:26.873  5878  5896 D BtGatt.AdvertiseManager: message : 1
,11-08 11:42:26.876  5878  5896 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 11:42:26.889  5878  5894 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 11:42:26.889  5878  5894 D BtGatt.GattService: Client app is not null!
11-08 11:42:26.891  5878  5888 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 11:42:26.892  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 11:42:26.892  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:26.892  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 11:42:26.892  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.892  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.892  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.892  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 11:42:26.893  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-08 11:42:26.893  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.893  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.893  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 11:42:26.893  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:26.896  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.896  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:42:26.896  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.896  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:26.897  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.897  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.897  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.898  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-08 11:42:26.898  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 11:42:26.900  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 11:42:26.902  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.904  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.904  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.904  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.905  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 11:42:26.905  5645  5645 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 11:42:26.905  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:26.905  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:26.905  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:42:26.907  5645  5692 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-08 11:42:26.907  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 11:42:26.908  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 11:42:26.909  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-08 11:42:26.909  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-08 11:42:26.909  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:42:26.909  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 11:42:26.914  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 11:42:26.914  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 11:42:26.914  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 11:42:26.918  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 11:42:26.919  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 11:42:26.919  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 11:42:26.924  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.924  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-08 11:42:26.924  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-08 11:42:26.924  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-08 11:42:26.925  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-08 11:42:26.925  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.926  5645  5692 D BluetoothAdapter: STATE_ON
11-08 11:42:26.929  5878  5918 D BtGatt.GattService: registerClient() - UUID=bd1fbdf2-be29-4a48-8466-44587020da1c
11-08 11:42:26.929  5878  5894 D BtGatt.GattService: onClientRegistered() - UUID=bd1fbdf2-be29-4a48-8466-44587020da1c, clientIf=5
11-08 11:42:26.930  5645  5655 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-08 11:42:26.931  5878  5919 D BtGatt.GattService: start scan with filters
11-08 11:42:26.934  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-08 11:42:26.934  5878  5897 D BtGatt.ScanManager: handling starting scan
11-08 11:42:26.934  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.934  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-08 11:42:26.935  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.935  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.935  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-08 11:42:26.935  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 11:42:26.935  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.935  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.935  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-08 11:42:26.935  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:26.937  5878  5897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d21aad
11-08 11:42:26.938  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.938  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-08 11:42:26.938  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.938  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.938  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-08 11:42:26.938  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.939  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 11:42:26.940  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:42:26.940  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.944  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.944  5878  5894 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-08 11:42:26.944  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.944  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:42:26.944  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:26.944  5878  5897 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-08 11:42:26.950  5878  5894 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-08 11:42:26.950  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:42:26.951  5878  5897 D BtGatt.ScanManager: Starting BLE batch scan
11-08 11:42:26.951  5878  5897 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-08 11:42:26.962  5878  5894 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-08 11:42:26.962  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:42:26.967  5878  5894 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-08 11:42:26.967  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 11:42:27.439  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-08 11:42:27.440  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 11:42:27.440  5645  5645 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 11:42:27.630   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-08 11:42:27.630   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-08 11:42:29.946  5645  5692 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-08 11:42:29.947  5645  5692 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,11-08 11:42:29.947  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-08 11:42:29.947  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-08 11:42:29.947  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-08 11:42:29.947  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-08 11:42:29.947  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-08 11:42:29.947  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-08 11:42:29.947  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-08 11:42:29.947  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-08 11:42:29.947  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-08 11:42:29.947  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,11-08 11:42:29.948  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 11:42:29.948  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-08 11:42:29.953  5645  5692 D BluetoothAdapter: STATE_ON
11-08 11:42:29.955  5878  5889 D BtGatt.GattService: stopScan() - queue size =1
11-08 11:42:29.957  5878  5906 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 11:42:29.958  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 11:42:29.958  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:29.959  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-08 11:42:29.959  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 11:42:29.959  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:29.961  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-08 11:42:29.961  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-08 11:42:29.963  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-08 11:42:29.963  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-08 11:42:29.964  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:29.965  5878  5878 D BtGatt.ScanManager: awakened up at time 117510
,11-08 11:42:29.967  5645  5692 D BluetoothAdapter: STATE_ON
11-08 11:42:29.971  5878  5889 D BtGatt.GattService: registerClient() - UUID=259ca505-b68b-431c-a4ba-b93f3b610cd6
11-08 11:42:29.972  5878  5894 D BtGatt.GattService: onClientRegistered() - UUID=259ca505-b68b-431c-a4ba-b93f3b610cd6, clientIf=5
,11-08 11:42:29.973  5645  5656 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-08 11:42:29.973  5878  5894 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-08 11:42:29.973  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 11:42:29.973  5878  5906 D BtGatt.GattService: start scan with filters
11-08 11:42:29.973  5878  5897 D BtGatt.ScanManager: stopping BLe Batch
,11-08 11:42:29.978  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-08 11:42:29.979  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:29.979  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-08 11:42:29.979  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:29.979  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:29.979  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-08 11:42:29.979  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-08 11:42:29.979  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:29.979  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:29.979  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 11:42:29.980  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 11:42:29.980  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 11:42:29.980  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 11:42:29.980  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 11:42:29.981  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 11:42:29.981  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 11:42:29.981  5878  5894 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-08 11:42:29.981  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-08 11:42:29.981  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 11:42:29.981  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 11:42:29.981  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 11:42:29.981  5645  5938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 11:42:29.981  5878  5897 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-08 11:42:29.982  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-08 11:42:29.982  5645  5938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 11:42:29.985  5645  5938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 11:42:29.979  5907  5907 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34860]" dev="sockfs" ino=34860 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 11:42:29.979  5907  5907 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34860]" dev="sockfs" ino=34860 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 11:42:29.989  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 11:42:29.989  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-08 11:42:29.995  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:29.995  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:29.995  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 11:42:29.995  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 11:42:29.995  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-08 11:42:29.995  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 11:42:29.996  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:29.996  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:29.996  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:29.996  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:29.996  5645  5692 D BluetoothAdapter: STATE_ON
,11-08 11:42:29.999  5878  5918 D BtGatt.GattService: registerClient() - UUID=4b51c60d-5c3b-4306-bcf1-065d434e768e
11-08 11:42:29.999  5878  5894 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-08 11:42:29.999  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:42:30.000  5878  5894 D BtGatt.GattService: current time is 117545074260
,11-08 11:42:30.000  5878  5894 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 44, 85, 56, -123, 53, 66, 1, -128, -100, 41, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, 37, -47, 14, -113, 116, -46, 1, -128, -87, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-08 11:42:30.001  5878  5897 D BtGatt.ScanManager: handling starting scan
11-08 11:42:30.002  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-08 11:42:30.003  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
11-08 11:42:30.003  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-08 11:42:30.003  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-08 11:42:30.003  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-08 11:42:30.004  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-08 11:42:30.004  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-08 11:42:30.005  5878  5894 D BtGatt.GattService: onClientRegistered() - UUID=4b51c60d-5c3b-4306-bcf1-065d434e768e, clientIf=6
11-08 11:42:30.005  5645  5656 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-08 11:42:30.006  5878  5896 D BtGatt.AdvertiseManager: message : 0
,11-08 11:42:30.010  5878  5896 D BtGatt.AdvertiseManager: starting multi advertising
11-08 11:42:30.010  5878  5894 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-08 11:42:30.010  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:42:30.010  5878  5897 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-08 11:42:30.020  5878  5894 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-08 11:42:30.024  5878  5894 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-08 11:42:30.024  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:42:30.025  5878  5897 D BtGatt.ScanManager: Starting BLE batch scan
11-08 11:42:30.025  5878  5897 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-08 11:42:30.029  5878  5894 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-08 11:42:30.030  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:30.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 11:42:30.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.030  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.030  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-08 11:42:30.031  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-08 11:42:30.031  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-08 11:42:30.032  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 11:42:30.032  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.035  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.035  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.035  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:30.035  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 11:42:30.036  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
,11-08 11:42:30.036  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 11:42:30.036  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=115395779241}
11-08 11:42:30.037  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 11:42:30.037  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-87, mTimestampNanos=114995779241}
11-08 11:42:30.037  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 11:42:30.037  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-76, mTimestampNanos=114895779241}
11-08 11:42:30.037  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 11:42:30.037  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-84, mTimestampNanos=115395779241}
11-08 11:42:30.038  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 11:42:30.038  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=115995779241}
11-08 11:42:30.038  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 11:42:30.038  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=42:35:85:38:55:2C, mScanRecord=ScanRecord [mAdvertiseFlags=26, mServiceUuids=null, mManufacturerSpecificData={76=[16, 2, 3, 0]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-100, mTimestampNanos=115495779241}
11-08 11:42:30.038  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-08 11:42:30.038  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=115445779241}
11-08 11:42:30.038  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-08 11:42:30.038  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-08 11:42:30.039  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 11:42:30.039  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 11:42:30.039  5645  5645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:30.039  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 11:42:30.039  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-08 11:42:30.039  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-08 11:42:30.039  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 11:42:30.039  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 11:42:30.039  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,11-08 11:42:30.039  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 11:42:30.039  5878  5894 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-08 11:42:30.039  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:42:30.043  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 11:42:30.043  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-08 11:42:30.043  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 11:42:30.043  5645  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-08 11:42:30.044  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 11:42:30.044  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 11:42:30.044  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-08 11:42:30.045  5878  5894 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-08 11:42:30.045  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 11:42:30.545  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-08 11:42:30.545  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-08 11:42:30.545  5645  5645 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 11:42:32.632   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:33.042  5645  5692 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-08 11:42:33.043  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-08 11:42:33.043  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 11:42:33.043  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-08 11:42:33.043  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-08 11:42:33.044  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 11:42:33.044  5645  5938 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-08 11:42:33.044  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 11:42:33.044  5645  5938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 11:42:33.044  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-08 11:42:33.044  5645  5938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 11:42:33.044  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-08 11:42:33.044  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 11:42:33.045  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cae8b1 removed from the list
11-08 11:42:33.045  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 11:42:33.045  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-08 11:42:33.045  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 11:42:33.045  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 11:42:33.045  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 11:42:33.045  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-08 11:42:33.046  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.046  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.046  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-08 11:42:33.049  5645  5692 D BluetoothAdapter: STATE_ON
11-08 11:42:33.050  5878  5906 D BtGatt.GattService: stopScan() - queue size =1
,11-08 11:42:33.052  5878  5919 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 11:42:33.053  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 11:42:33.054  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.054  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-08 11:42:33.054  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.054  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.054  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 11:42:33.055  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-08 11:42:33.055  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.055  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.055  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-08 11:42:33.056  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.062  5878  5878 D BtGatt.ScanManager: awakened up at time 120606
11-08 11:42:33.063  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.063  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 11:42:33.063  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.063  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.063  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.064  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:33.064  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 11:42:33.064  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.065  5878  5896 D BtGatt.AdvertiseManager: message : 1
11-08 11:42:33.066  5878  5896 D BtGatt.AdvertiseManager: stop advertise for client 6
11-08 11:42:33.067  5878  5894 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-08 11:42:33.067  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:42:33.067  5878  5897 D BtGatt.ScanManager: stopping BLe Batch
,11-08 11:42:33.076  5878  5894 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-08 11:42:33.076  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:42:33.076  5878  5897 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-08 11:42:33.081  5878  5894 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-08 11:42:33.082  5878  5894 D BtGatt.GattService: Client app is not null!
,11-08 11:42:33.082  5878  5915 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-08 11:42:33.083  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 11:42:33.083  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.083  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 11:42:33.083  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:33.083  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:33.083  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
,11-08 11:42:33.084  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-08 11:42:33.084  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 11:42:33.084  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.084  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.084  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 11:42:33.084  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.085  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.085  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:42:33.085  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.085  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.085  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.085  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.086  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.086  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 11:42:33.086  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 11:42:33.086  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 11:42:33.086  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.087  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.087  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.088  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 11:42:33.088  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3313196 removed from the list
11-08 11:42:33.088  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:33.088  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
,11-08 11:42:33.088  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 11:42:33.088  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 11:42:33.088  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 11:42:33.088  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 11:42:33.090  5645  5692 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-08 11:42:33.090  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-08 11:42:33.090  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 11:42:33.090  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 11:42:33.090  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 11:42:33.091  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-08 11:42:33.091  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-08 11:42:33.092  5645  5692 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-08 11:42:33.093  5645  5692 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-08 11:42:33.093  5645  5692 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-08 11:42:33.094  5645  5692 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-08 11:42:33.095  5645  5692 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-08 11:42:33.096  5645  5692 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-08 11:42:33.096  5645  5692 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-08 11:42:33.097  5645  5692 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-08 11:42:33.109  5878  5894 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-08 11:42:33.110  5878  5894 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 11:42:33.110  5878  5894 D BtGatt.GattService: current time is 120654930970
,11-08 11:42:33.110  5878  5894 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -89, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 44, 85, 56, -123, 53, 66, 1, -128, -103, 21, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, 71, -122, -77, 84, 69, -12, 1, -128, -84, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-08 11:42:33.110  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-08 11:42:33.110  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-08 11:42:33.110  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
11-08 11:42:33.110  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-08 11:42:33.111  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-08 11:42:33.111  5878  5894 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-08 11:42:33.522   929  2985 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-08 11:42:33.589  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 11:42:33.633   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:34.634   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:34.887   929  2985 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-08 11:42:35.102  5645  5692 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-08 11:42:35.242  5645  5941 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 11:42:35.242  5645  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 11:42:35.636   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:35.909   929  2985 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-08 11:42:35.910   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-08 11:42:35.911   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 11:42:35.919   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-08 11:42:35.943   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-08 11:42:35.947  5933  5933 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-08 11:42:36.081  5645  5941 W !!      : call onHalfStreamCopied
,11-08 11:42:36.082  5645  5941 I testCopyDataAndClose: closing input stream
,11-08 11:42:36.405  5933  5933 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-08 11:42:36.441  5933  5933 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-08 11:42:36.443  5933  5933 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-08 11:42:36.452   929  2985 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-08 11:42:36.452   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 11:42:36.452   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-08 11:42:36.468   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 11:42:36.486   509   927 D CommandListener: Setting iface cfg
,11-08 11:42:36.492   929  2985 D WifiStateMachine: Start Dhcp Watchdog 2
,11-08 11:42:36.498   929  5945 D DhcpClient: Receive thread started
,11-08 11:42:36.502   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-08 11:42:36.502   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-08 11:42:36.503   929  2987 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-08 11:42:36.584   929  2985 E native  : do suspend false
,11-08 11:42:36.601   929  5944 D DhcpClient: Broadcasting DHCPDISCOVER
,11-08 11:42:36.618   929  5945 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172718, domain null
11-08 11:42:36.619   929  5944 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172718 seconds
,11-08 11:42:36.621   929  5944 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-08 11:42:36.637   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:36.649   929  5945 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-08 11:42:36.649   929  5944 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-08 11:42:36.651   509   927 D CommandListener: Setting iface cfg
,11-08 11:42:36.653   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-08 11:42:36.656   929  5944 D DhcpClient: Scheduling renewal in 86399s
,11-08 11:42:36.661   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-08 11:42:36.661   929  2985 D WifiConfigStore: No blacklist allowed without epno enabled
,11-08 11:42:36.661   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-08 11:42:36.664   929  2985 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-08 11:42:36.668   929  2987 D ConnectivityService: Adding iface wlan0 to network 101
,11-08 11:42:36.694   929  2987 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-08 11:42:36.694   929  2987 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-08 11:42:36.696   929  2987 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-08 11:42:36.697   929  2987 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-08 11:42:36.698   929  2987 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-08 11:42:36.703   929  2987 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-08 11:42:36.707   929  2987 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-08 11:42:36.707   929  2987 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-08 11:42:36.707   929  2987 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,11-08 11:42:36.707   929  2985 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-08 11:42:36.707   929  2987 D ConnectivityService:    accepting network in place of null
11-08 11:42:36.707   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 11:42:36.708   929  2987 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-08 11:42:36.722   929  5943 D NetlinkSocketObserver: NeighborEvent{elapsedMs=124267, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-08 11:42:36.729   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 11:42:36.750   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 11:42:36.753   929  2987 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-08 11:42:36.753  3777  3900 W QCNEJ   : |CORE| network available: 101
,11-08 11:42:36.753   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-08 11:42:36.754   929  2987 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-08 11:42:36.756   929   946 D Tethering: MasterInitialState.processMessage what=3
11-08 11:42:36.759  3777  3900 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-08 11:42:36.769  3994  3994 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-08 11:42:36.760  3777  3900 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-08 11:42:36.764  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:36.764  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:36.764  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:36.764  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:36.764  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:36.764  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:42:36.764  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:42:36.764  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 11:42:36.770  3777  3900 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-08 11:42:36.767  4013  4013 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-08 11:42:36.774  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 11:42:36.775  4013  4013 D SystemUpdateService: onCreate
11-08 11:42:36.778  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 11:42:36.778  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 11:42:36.778  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 11:42:36.778  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 11:42:36.778  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 11:42:36.778  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 11:42:36.778  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 11:42:36.778  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 11:42:36.779  4013  4013 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-08 11:42:36.780  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 11:42:36.788  4013  4013 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-08 11:42:36.789  4013  4310 I iu.UploadsManager: num queued entries: 0
,11-08 11:42:36.790  4013  4310 I iu.UploadsManager: num updated entries: 0
11-08 11:42:36.790  4013  4310 I iu.SyncManager: NEXT; no task
,11-08 11:42:36.791  4013  5954 I SystemUpdateService: active receiver: enabled
,11-08 11:42:36.793   929  5942 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-08 11:42:36.800  4013  4013 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-08 11:42:36.801  4013  4013 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 11:42:36.803  5730  5730 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 11:42:36.808  5730  5730 D SprintDMHelper: simOperator: 
11-08 11:42:36.808  5730  5730 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 11:42:36.810  4013  5954 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 11:42:36.830  4013  5954 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-08 11:42:36.830  4013  5954 I SystemUpdateService: now status is 0 (complete)
,11-08 11:42:36.830  4013  5954 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-08 11:42:36.832  4013  5954 I SystemUpdateService: file has been verified
11-08 11:42:36.832  4013  5954 I SystemUpdateService: OTA package size = 21989297
,11-08 11:42:36.840  4013  5954 I SystemUpdateService: showing system update notification
,11-08 11:42:36.847   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 11:42:36.848  4013  4013 D SystemUpdateService: onDestroy
,11-08 11:42:36.865  5645  5941 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 11:42:36.865  5645  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 11:42:36.865  5645  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 11:42:36.865  5645  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 11:42:36.865  5645  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-08 11:42:36.865  5645  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 11:42:36.865  5645  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 11:42:36.865  5645  5941 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-08 11:42:36.865  5645  5941 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-08 11:42:36.865  5645  5941 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 11:42:36.865  5645  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-08 11:42:36.942   929  5942 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 08 Nov 2016 10:42:36 GMT], X-Android-Received-Millis=[1478601756941], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478601756815]}
,11-08 11:42:36.942   929  2987 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-08 11:42:36.943   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-08 11:42:36.943   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-08 11:42:36.944   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-08 11:42:37.637   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-08 11:42:37.754   929  2987 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-08 11:42:38.035   929  2985 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,11-08 11:42:41.217  5645  5692 I StreamCopyingThreadTest: Starting test: testRun
,11-08 11:42:41.221  5645  5962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:42:41.221  5645  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 11:42:42.639   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:43.640   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:44.643   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:44.713   929  2987 D ConnectivityService: handlePromptUnvalidated 101
,11-08 11:42:45.645   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:46.228  5645  5963 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-08 11:42:46.231  5645  5692 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-08 11:42:46.346  5645  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 11:42:46.346  5645  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 11:42:46.647   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:47.647   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-08 11:42:48.026  5645  5964 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 11:42:48.026  5645  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 11:42:48.027  5645  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 11:42:48.027  5645  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 11:42:48.027  5645  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-08 11:42:48.027  5645  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 11:42:48.027  5645  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 11:42:48.027  5645  5964 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-08 11:42:48.027  5645  5964 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-08 11:42:48.027  5645  5964 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 11:42:48.027  5645  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-08 11:42:49.081  3686  3721 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-08 11:42:49.082  3686  3721 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-08 11:42:49.117  3595  3595 I ConfigService: onCreate
,11-08 11:42:52.799  5645  5692 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-08 11:42:52.802  5645  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:42:52.802  5645  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 11:42:52.802  5645  5966 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:42:52.802  5645  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 11:42:52.802  5645  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 11:42:52.802  5645  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 11:42:52.803  5645  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-08 11:42:52.803  5645  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 11:42:52.803  5645  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-08 11:42:52.803  5645  5966 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-08 11:42:52.803  5645  5966 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-08 11:42:52.803  5645  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:42:52.803  5645  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-08 11:42:52.805  5645  5692 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-08 11:42:52.805  5645  5692 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-08 11:42:52.806  5645  5692 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-08 11:42:52.808  5645  5967 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:42:52.808  5645  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 11:42:52.809  5645  5967 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
11-08 11:42:52.809  5645  5967 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:42:52.809  5645  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-08 11:42:52.809  5645  5967 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-08 11:42:52.810  5645  5967 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-08 11:42:52.810  5645  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-08 11:42:52.811  5645  5692 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-08 11:42:52.811  5645  5692 E com.test.thalitest.ThaliTestRunner: 
11-08 11:42:52.811  5645  5692 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-08 11:42:52.811  5645  5692 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 11:42:52.812  5645,  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 11:42:52.812  5645  5692 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-08 11:42:52.813  5645  5692 E com.test.t,halitest.ThaliTestRunner: Expected: is <true>
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
,11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: ,	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: ,	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290),
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
,11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95),
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:42:52.813  5645  5692 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 11:42:52.815  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG UnitTest_app: 'Running unit tests'
11-08 11:42:52.815  5645  5692 I jxcore-log: 
11-08 11:42:52.815  5645  5692 I jxcore-log: *Native tests were executed*
11-08 11:42:52.815  5645  5692 I jxcore-log: 
11-08 11:42:52.815  5645  5692 I jxcore-log: Total number of executed tests:  82
11-08 11:42:52.815  5645  5692 I jxcore-log: 
11-08 11:42:52.815  5645  5692 I jxcore-log: Number of passed tests:  80
11-08 11:42:52.815  5645  5692 I jxcore-log: 
11-08 11:42:52.815  5645  5692 I jxcore-log: Number of failed tests:  2
11-08 11:42:52.815  5645  5692 I jxcore-log: 
11-08 11:42:52.815  5645  5692 I jxcore-log: Number of ignored tests:  0
11-08 11:42:52.815  5645  5692 I jxcore-log: 
11-08 11:42:52.816  5645  5692 I jxcore-log: Total duration:  42654
11-08 11:42:52.816  5645  5692 I jxcore-log: 
11-08 11:42:52.816  5645  5692 I jxcore-log: Failed to execute UT.
11-08 11:42:52.816  5645  5692 I jxcore-log: 
11-08 11:42:52.817  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-08 11:42:52.817  5645  5692 I jxcore-log: 
11-08 11:42:52.818  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-08 11:42:52.818  5645  5692 I jxcore-log: 
11-08 11:42:52.822  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:42:52.822  5645  5692 I jxcore-log: 
11-08 11:42:52.822  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.822  5645  5692 I jxcore-log: 
11-08 11:42:52.823  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:42:52.823  5645  5692 I jxcore-log: 
11-08 11:42:52.824  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.824  5645  5692 I jxcore-log: 
11-08 11:42:52.825  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:42:52.825  5645  5692 I jxcore-log: 
11-08 11:42:52.825  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.825  5645  5692 I jxcore-log: 
11-08 11:42:52.826  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 11:42:52.826  5645  5692 I jxcore-log: 
11-08 11:42:52.826  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 11:42:52.826  5645  5692 I jxcore-log: 
11-08 11:42:52.826  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 11:42:52.826  5645  5692 I jxcore-log: 
11-08 11:42:52.827  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 11:42:52.827  5645  5692 I jxcore-log: 
11-08 11:42:52.827  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":,"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:42:52.827  5645  5692 I jxcore-log: 
11-08 11:42:52.827  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.827  5645  5692 I jxcore-log: 
11-08 11:42:52.827  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.827  5645  5692 I jxcore-log: 
11-08 11:42:52.827  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.827  5645  5692 I jxcore-log: 
11-08 11:42:52.828  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.828  5645  5692 I jxcore-log: 
11-08 11:42:52.828  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.828  5645  5692 I jxcore-log: 
11-08 11:42:52.828  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.828  5645  5692 I jxcore-log: 
11-08 11:42:52.828  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.828  5645  5692 I jxcore-log: 
11-08 11:42:52.828  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:42:52.828  5645  5692 I jxcore-log: 
11-08 11:42:52.829  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.829  5645  5692 I jxcore-log: 
11-08 11:42:52.829  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:42:52.829  5645  5692 I jxcore-log: 
11-08 11:42:52.829  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.829  5645  5692 I jxcore-log: 
11-08 11:42:52.829  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:42:52.829  5645  5692 I jxcore-log: 
11-08 11:42:52.829  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.829  5645  5692 I jxcore-log: 
11-08 11:42:52.830  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 11:42:52.830  5645  5692 I jxcore-log: 
11-08 11:42:52.830  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.830  5645  5692 I jxcore-log: 
11-08 11:42:52.830  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.830  5645  5692 I jxcore-log: 
11-08 11:42:52.831  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.831  5645  5692 I jxcore-log: 
11-08 11:42:52.831  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.831  5645  5692 I jxcore-log: 
11-08 11:42:52.832  5645  5692 I jxcore-log: 2,016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.832  5645  5692 I jxcore-log: 
11-08 11:42:52.832  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.832  5645  5692 I jxcore-log: 
11-08 11:42:52.833  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.833  5645  5692 I jxcore-log: 
11-08 11:42:52.833  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.833  5645  5692 I jxcore-log: 
11-08 11:42:52.833  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.833  5645  5692 I jxcore-log: 
11-08 11:42:52.833  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.833  5645  5692 I jxcore-log: 
11-08 11:42:52.833  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.833  5645  5692 I jxcore-log: 
11-08 11:42:52.834  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.834  5645  5692 I jxcore-log: 
11-08 11:42:52.834  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.834  5645  5692 I jxcore-log: 
11-08 11:42:52.834  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.834  5645  5692 I jxcore-log: 
11-08 11:42:52.834  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.834  5645  5692 I jxcore-log: 
11-08 11:42:52.834  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.834  5645  5692 I jxcore-log: 
11-08 11:42:52.834  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.834  5645  5692 I jxcore-log: 
11-08 11:42:52.835  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.835  5645  5692 I jxcore-log: 
11-08 11:42:52.835  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.835  5645  5692 I jxcore-log: 
11-08 11:42:52.835  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.835  5645  5692 I jxcore-log: 
11-08 11:42:52.835  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.835  5645  5692 I jxcore-log: 
11-08 11:42:52.835  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.835  5645  5692 I jxcore-log: 
11-08 11:42:52.836  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.836  5645  5692 I jxcore-log: 
11-08 11:42:52.836  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.836  5645  5692 I jxcore-log: 
11-08 11:42:52.836  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.836  5645  5692 I jxcore-log: 
11-08 11:42:52.836  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.836  5645  5692 I jxcore-log: 
11-08 11:42:52.836  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.836  5645  5692 I jxcore-log: 
11-08 11:42:52.837  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.837  5645  5692 I jxcore-log: 
11-08 11:42:52.837  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.837  5645  5692 I jxcore-log: 
11-08 11:42:52.837  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.837  5645  5692 I jxcore-log: 
11-08 11:42:52.837  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:42:52.837  5645  5692 I jxcore-log: 
11-08 11:42:52.837  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.837  5645  5692 I jxcore-log: 
11-08 11:42:52.837  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:42:52.837  5645  5692 I jxcore-log: 
11-08 11:42:52.838  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.838  5645  5692 I jxcore-log: 
11-08 11:42:52.838  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 11:42:52.838  5645  5692 I jxcore-log: 
11-08 11:42:52.838  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.838  5645  5692 I jxcore-log: 
11-08 11:42:52.838  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.838  5645  5692 I jxcore-log: 
11-08 11:42:52.838  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.838  5645  5692 I jxcore-log: 
11-08 11:42:52.839  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.839  5645  5692 I jxcore-log: 
11-08 11:42:52.839  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.839  5645  5692 I jxcore-log: 
11-08 11:42:52.839  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.839  5645  5692 I jxcore-log: 
11-08 11:42:52.839  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.839  5645  5692 I jxcore-log: 
11-08 11:42:52.839  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 11:42:52.839  5645  5692 I jxcore-log: 
11-08 11:42:52.839  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.839  5645  5692 I jxcore-log: 
11-08 11:42:52.840  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 11:42:52.840  5645  5692 I jxcore-log: 
11-08 11:42:52.840  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-08 11:42:52.840  5645  5692 I jxcore-log: 
11-08 11:42:52.840  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-08 11:42:52.840  5645  5692 I jxcore-log: 
11-08 11:42:52.840  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 11:42:52.840  5645  5692 I jxcore-log: 
11-08 11:42:52.841  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:42:52.841  5645  5692 I jxcore-log: 
11-08 11:42:52.841  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.841  5645  5692 I jxcore-log: 
11-08 11:42:52.841  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 11:42:52.841  5645  5692 I jxcore-log: 
11-08 11:42:52.841  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 11:42:52.841  5645  5692 I jxcore-log: 
11-08 11:42:52.844  5645  5645 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-08 11:42:52.846  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-08 11:42:52.846  5645  5692 I jxcore-log: 
11-08 11:42:52.847  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - WARN testUtils: 'myNameCallback not set!'
11-08 11:42:52.847  5645  5692 I jxcore-log: 
11-08 11:42:52.847  5645  5692 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
11-08 11:42:52.848  5645  5692 I jxcore-log: 2016-11-08 10:42:52 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-08 11:42:52.848  5645  5692 I jxcore-log: 
,11-08 11:42:54.150  3595  3595 I ConfigService: onDestroy
,11-08 11:42:54.850  5645  5692 I jxcore-log: 2016-11-08 10:42:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-08 11:42:54.850  5645  5692 I jxcore-log: 
,11-08 11:42:55.174  5645  5692 I jxcore-log: 2016-11-08 10:42:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-08 11:42:55.174  5645  5692 I jxcore-log: 
,11-08 11:42:55.186  5645  5692 I jxcore-log: 2016-11-08 10:42:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-08 11:42:55.186  5645  5692 I jxcore-log: 
,11-08 11:42:56.273  5645  5692 I jxcore-log: 2016-11-08 10:42:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-08 11:42:56.273  5645  5692 I jxcore-log: 
,11-08 11:42:56.439  5645  5692 I jxcore-log: 2016-11-08 10:42:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-08 11:42:56.439  5645  5692 I jxcore-log: 
,11-08 11:42:56.444  5645  5692 I jxcore-log: 2016-11-08 10:42:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-08 11:42:56.444  5645  5692 I jxcore-log: 
,11-08 11:42:56.449  5645  5692 I jxcore-log: 2016-11-08 10:42:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-08 11:42:56.449  5645  5692 I jxcore-log: 
,11-08 11:42:56.923  5645  5692 I jxcore-log: 2016-11-08 10:42:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-08 11:42:56.923  5645  5692 I jxcore-log: 
,11-08 11:42:56.966  5645  5692 I jxcore-log: 2016-11-08 10:42:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-08 11:42:56.966  5645  5692 I jxcore-log: 
,11-08 11:42:56.979  5645  5692 I jxcore-log: 2016-11-08 10:42:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-08 11:42:56.979  5645  5692 I jxcore-log: 
,11-08 11:42:56.983  5645  5692 I jxcore-log: 2016-11-08 10:42:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-08 11:42:56.983  5645  5692 I jxcore-log: 
,11-08 11:42:57.260  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-08 11:42:57.260  5645  5692 I jxcore-log: 
,11-08 11:42:57.398  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-08 11:42:57.398  5645  5692 I jxcore-log: 
,11-08 11:42:57.648   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:57.763  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-08 11:42:57.763  5645  5692 I jxcore-log: 
,11-08 11:42:57.798  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-08 11:42:57.798  5645  5692 I jxcore-log: 
,11-08 11:42:57.804  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-08 11:42:57.804  5645  5692 I jxcore-log: 
,11-08 11:42:57.809  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-08 11:42:57.809  5645  5692 I jxcore-log: 
,11-08 11:42:57.816  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-08 11:42:57.816  5645  5692 I jxcore-log: 
,11-08 11:42:57.829  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-08 11:42:57.829  5645  5692 I jxcore-log: 
,11-08 11:42:57.835  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-08 11:42:57.835  5645  5692 I jxcore-log: 
,11-08 11:42:57.863  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-08 11:42:57.863  5645  5692 I jxcore-log: 
,11-08 11:42:57.900  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-08 11:42:57.900  5645  5692 I jxcore-log: 
,11-08 11:42:57.908  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-08 11:42:57.908  5645  5692 I jxcore-log: 
,11-08 11:42:57.914  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-08 11:42:57.914  5645  5692 I jxcore-log: 
,11-08 11:42:57.929  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-08 11:42:57.929  5645  5692 I jxcore-log: 
,11-08 11:42:57.933  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-08 11:42:57.933  5645  5692 I jxcore-log: 
,11-08 11:42:57.939  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-08 11:42:57.939  5645  5692 I jxcore-log: 
,11-08 11:42:57.944  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-08 11:42:57.944  5645  5692 I jxcore-log: 
,11-08 11:42:57.957  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-08 11:42:57.957  5645  5692 I jxcore-log: 
,11-08 11:42:57.964  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-08 11:42:57.964  5645  5692 I jxcore-log: 
,11-08 11:42:57.986  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-08 11:42:57.986  5645  5692 I jxcore-log: 
,11-08 11:42:57.997  5645  5692 I jxcore-log: 2016-11-08 10:42:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-08 11:42:57.997  5645  5692 I jxcore-log: 
,11-08 11:42:58.008  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-08 11:42:58.008  5645  5692 I jxcore-log: 
,11-08 11:42:58.018  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-08 11:42:58.018  5645  5692 I jxcore-log: 
,11-08 11:42:58.031  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-08 11:42:58.031  5645  5692 I jxcore-log: 
,11-08 11:42:58.041  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-08 11:42:58.041  5645  5692 I jxcore-log: 
,11-08 11:42:58.047  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-08 11:42:58.047  5645  5692 I jxcore-log: 
,11-08 11:42:58.053  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-08 11:42:58.053  5645  5692 I jxcore-log: 
,11-08 11:42:58.059  5645  5692 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-08 11:42:58.060  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - INFO testUtils: 'BLE multiple advertisement supported'
11-08 11:42:58.060  5645  5692 I jxcore-log: 
,11-08 11:42:58.164  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:42:58.164  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:42:58.164  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:42:58.164  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:42:58.164  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:42:58.164  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:42:58.164  5645  5692 I jxcore-log: 
,11-08 11:42:58.489  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:42:58.489  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:42:58.489  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:42:58.489  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:42:58.489  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:42:58.489  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:42:58.489  5645  5692 I jxcore-log: 
,11-08 11:42:58.491  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:42:58.491  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:42:58.491  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:42:58.491  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:42:58.491  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:42:58.491  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:42:58.491  5645  5692 I jxcore-log: 
,11-08 11:42:58.649   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:58.837  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:42:58.837  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:42:58.837  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:42:58.837  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:42:58.837  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:42:58.837  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:42:58.837  5645  5692 I jxcore-log: 
,11-08 11:42:58.839  5645  5692 I jxcore-log: 2016-11-08 10:42:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:42:58.839  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:42:58.839  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:42:58.839  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:42:58.839  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:42:58.839  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:42:58.839  5645  5692 I jxcore-log: 
,11-08 11:42:59.651   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:42:59.930  5645  5692 I jxcore-log: 2016-11-08 10:42:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:42:59.930  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:42:59.930  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:42:59.930  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:42:59.930  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:42:59.930  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:42:59.930  5645  5692 I jxcore-log: 
,11-08 11:42:59.937  5645  5692 I jxcore-log: 2016-11-08 10:42:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:42:59.937  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:42:59.937  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:42:59.937  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:42:59.937  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:42:59.937  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:42:59.937  5645  5692 I jxcore-log: 
,11-08 11:43:00.652   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:43:00.981  5645  5692 I jxcore-log: 2016-11-08 10:43:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:00.981  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:00.981  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:00.981  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:00.981  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:00.981  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:00.981  5645  5692 I jxcore-log: 
,11-08 11:43:00.989  5645  5692 I jxcore-log: 2016-11-08 10:43:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:00.989  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:00.989  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:00.989  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:00.989  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:00.989  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:00.989  5645  5692 I jxcore-log: 
,11-08 11:43:01.653   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 11:43:02.032  5645  5692 I jxcore-log: 2016-11-08 10:43:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:02.032  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:02.032  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:02.032  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:02.032  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:02.032  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:02.032  5645  5692 I jxcore-log: 
,11-08 11:43:02.037  5645  5692 I jxcore-log: 2016-11-08 10:43:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:02.037  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:02.037  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:02.037  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:02.037  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:02.037  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:02.037  5645  5692 I jxcore-log: 
,11-08 11:43:02.653   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-08 11:43:03.107  5645  5692 I jxcore-log: 2016-11-08 10:43:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:03.107  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:03.107  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:03.107  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:03.107  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:03.107  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:03.107  5645  5692 I jxcore-log: 
,11-08 11:43:03.112  5645  5692 I jxcore-log: 2016-11-08 10:43:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:03.112  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:03.112  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:03.112  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:03.112  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:03.112  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:03.112  5645  5692 I jxcore-log: 
,11-08 11:43:03.725   929  5943 D NetlinkSocketObserver: NeighborEvent{elapsedMs=151270, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-08 11:43:04.148  5645  5692 I jxcore-log: 2016-11-08 10:43:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:04.148  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:04.148  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:04.148  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:04.148  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:04.148  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:04.148  5645  5692 I jxcore-log: 
,11-08 11:43:04.152  5645  5692 I jxcore-log: 2016-11-08 10:43:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:04.152  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:04.152  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:04.152  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:04.152  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:04.152  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:04.152  5645  5692 I jxcore-log: 
,11-08 11:43:05.237   929   949 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
11-08 11:43:05.245  3686  3686 I Keyboard.Facilitator: onFinishInput()
11-08 11:43:05.240  3450  3450 W Binder_6: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32890]" dev="sockfs" ino=32890 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:43:05.243  3450  3450 W Binder_6: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[32890]" dev="sockfs" ino=32890 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:43:05.265   929   949 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 11:43:05.265   929   949 I Adreno  : Build Date                       : 12/06/15
11-08 11:43:05.265   929   949 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 11:43:05.265   929   949 I Adreno  : Local Branch                     : mybranch17112971
11-08 11:43:05.265   929   949 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 11:43:05.265   929   949 I Adreno  : Remote Branch                    : NONE
11-08 11:43:05.265   929   949 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 11:43:05.303   381  2977 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (153 us)
,11-08 11:43:05.743  5645  5692 I jxcore-log: 2016-11-08 10:43:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:05.743  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:05.743  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:05.743  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:05.743  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:05.743  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:05.743  5645  5692 I jxcore-log: 
,11-08 11:43:05.755  5645  5692 I jxcore-log: 2016-11-08 10:43:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:05.755  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:05.755  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:05.755  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:05.755  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:05.755  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:05.755  5645  5692 I jxcore-log: 
,11-08 11:43:06.003  5645  5645 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-08 11:43:06.004  5645  5645 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-08 11:43:06.032   929   949 I sensors : batch
,11-08 11:43:06.032   929   949 V KeyguardServiceDelegate: onScreenTurnedOff()
11-08 11:43:06.033  5645  5645 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6a11030 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@45627a, 16908290=android.view.AbsSavedState$1@45627a}, android:focusedViewId=100}]}]
11-08 11:43:06.034  5645  5645 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-08 11:43:06.034   929   949 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-08 11:43:06.034  5645  5645 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-08 11:43:06.034   929   949 I sensors : activate
11-08 11:43:06.035  5645  5645 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,11-08 11:43:06.036   381   381 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f79943c00
,11-08 11:43:06.036   929   947 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-08 11:43:06.036   381   381 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,11-08 11:43:06.044   929  2696 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-08 11:43:06.046   929  2696 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-08 11:43:06.253   509   927 D TetherController: Setting IP forward enable = 1
,11-08 11:43:06.320   381   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-08 11:43:06.321   381   381 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
11-08 11:43:06.322   929  3098 D SurfaceControl: Excessive delay in setPowerMode(): 287ms
,11-08 11:43:06.328   929   949 I DreamManagerService: Entering dreamland.
11-08 11:43:06.328   929   949 I PowerManagerService: Dozing...
,11-08 11:43:06.328   929   944 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-08 11:43:06.343   939   939 W Binder_1: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[32714]" dev="sockfs" ino=32714 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:43:06.343   939   939 W Binder_1: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[32714]" dev="sockfs" ino=32714 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:43:06.348   929  3858 I sensors : batch
11-08 11:43:06.348   929  3858 I sensors : activate
,11-08 11:43:06.352   929  2696 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-08 11:43:06.352   929  2696 I hubconnection: sensorhub said: 'activate 21 enable:1'
11-08 11:43:06.356   514  3037 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-08 11:43:06.361   929  2985 E native  : do suspend false
,11-08 11:43:06.367   929  2985 D WifiConfigStore: No blacklist allowed without epno enabled
,11-08 11:43:06.376  3816  4779 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
11-08 11:43:06.376  3816  4779 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-08 11:43:06.376  3816  4779 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-08 11:43:06.377   527  1025 D         : oem-qmi: Connection accepted
11-08 11:43:06.377   527  1025 D         : oem-qmi: Waiting to accept connection
,11-08 11:43:06.378   929   929 I sensors : activate
,11-08 11:43:06.379   514  3038 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-08 11:43:06.379  3816  4779 D         : oem_qmi_lib:output 0
11-08 11:43:06.379  3816  4779 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
11-08 11:43:06.381   929  2696 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-08 11:43:06.381   929  2985 E native  : do suspend true
,11-08 11:43:06.399  3816  4779 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-08 11:43:06.400  3816  4779 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-08 11:43:06.400  3816  4779 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-08 11:43:06.400   527  1025 D         : oem-qmi: Connection accepted
11-08 11:43:06.400   527  1025 D         : oem-qmi: Waiting to accept connection
,11-08 11:43:06.402  3816  4779 D         : oem_qmi_lib:output 0
,11-08 11:43:06.402  3816  4779 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-08 11:43:06.791  5645  5692 I jxcore-log: 2016-11-08 10:43:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:06.791  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:06.791  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:06.791  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:06.791  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:06.791  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:06.791  5645  5692 I jxcore-log: 
,11-08 11:43:06.797  5645  5692 I jxcore-log: 2016-11-08 10:43:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:06.797  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:06.797  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:06.797  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:06.797  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:06.797  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:06.797  5645  5692 I jxcore-log: 
,11-08 11:43:06.860   929  2985 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,11-08 11:43:07.876  5645  5692 I jxcore-log: 2016-11-08 10:43:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:07.876  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:07.876  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:07.876  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:07.876  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:07.876  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:07.876  5645  5692 I jxcore-log: 
,11-08 11:43:07.882  5645  5692 I jxcore-log: 2016-11-08 10:43:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:07.882  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:07.882  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:07.882  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:07.882  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:07.882  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:07.882  5645  5692 I jxcore-log: 
,11-08 11:43:08.924  5645  5692 I jxcore-log: 2016-11-08 10:43:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:08.924  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:08.924  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:08.924  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:08.924  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:08.924  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:08.924  5645  5692 I jxcore-log: 
,11-08 11:43:08.930  5645  5692 I jxcore-log: 2016-11-08 10:43:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:08.930  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:08.930  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:08.930  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:08.930  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:08.930  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:08.930  5645  5692 I jxcore-log: 
,11-08 11:43:09.145   929  5943 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-08 11:43:09.917  3755  4484 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-08 11:43:09.969  5645  5692 I jxcore-log: 2016-11-08 10:43:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:09.969  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:09.969  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:09.969  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:09.969  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:09.969  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:09.969  5645  5692 I jxcore-log: 
,11-08 11:43:09.974  5645  5692 I jxcore-log: 2016-11-08 10:43:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:09.974  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:09.974  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:09.974  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:09.974  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:09.974  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:09.974  5645  5692 I jxcore-log: 
,11-08 11:43:11.019  5645  5692 I jxcore-log: 2016-11-08 10:43:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:11.019  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:11.019  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:11.019  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:11.019  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:11.019  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:11.019  5645  5692 I jxcore-log: 
,11-08 11:43:11.023  5645  5692 I jxcore-log: 2016-11-08 10:43:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:11.023  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:11.023  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:11.023  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:11.023  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:11.023  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:11.023  5645  5692 I jxcore-log: 
,11-08 11:43:12.074  5645  5692 I jxcore-log: 2016-11-08 10:43:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:12.074  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:12.074  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:12.074  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:12.074  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:12.074  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:12.074  5645  5692 I jxcore-log: 
,11-08 11:43:12.080  5645  5692 I jxcore-log: 2016-11-08 10:43:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:12.080  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:12.080  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:12.080  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:12.080  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:12.080  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:12.080  5645  5692 I jxcore-log: 
,11-08 11:43:13.715  5645  5692 I jxcore-log: 2016-11-08 10:43:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 11:43:13.715  5645  5692 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 11:43:13.715  5645  5692 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 11:43:13.715  5645  5692 I jxcore-log: emit@events.js:82:1
11-08 11:43:13.715  5645  5692 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 11:43:13.715  5645  5692 I jxcore-log: emit@events.js:82:1'
11-08 11:43:13.715  5645  5692 I jxcore-log: 
,11-08 11:43:13.728  5645  5692 E jxcore  : Error!: error is undefined
11-08 11:43:13.728  5645  5692 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-08 11:43:13.731  5645  5692 I jxcore-log: 2016-11-08 10:43:13 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-08 11:43:13.731  5645  5692 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-08 11:43:13.731  5645  5692 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-08 11:43:13.731  5645  5692 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-08 11:43:13.731  5645  5692 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-08 11:43:13.731  5645  5692 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-08 11:43:13.731  5645  5692 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-08 11:43:13.731  5645  5692 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-08 11:43:13.733  5645  5692 I jxcore-log: 2016-11-08 10:43:13 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-08 11:43:13.733  5645  5692 I jxcore-log: 
,11-08 11:43:13.735  5645  5692 E jxcore-log: TypeError: 
11-08 11:43:13.735  5645  5692 E jxcore-log: error is undefined
11-08 11:43:13.736  5645  5692 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-08 11:43:13.736  5645  5692 E jxcore-log: 
,11-08 11:43:13.833   929  3450 D GraphicsStats: Buffer count: 2
,11-08 11:43:13.833   929  3877 I WindowState: WIN DEATH: Window{f3d59a5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-08 11:43:13.835   929  2986 D WifiService: Client connection lost with reason: 4
,11-08 11:43:13.850   929  3450 I ActivityManager: Process com.test.thalitest (pid 5645) has died
,11-08 11:43:13.851   529   529 I Zygote  : Process 5645 exited cleanly (139)
,11-08 11:43:13.865   929  3450 I ActivityManager: Start proc 6014:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-08 11:43:13.921  6014  6014 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-08 11:43:13.938  6014  6014 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-08 11:43:13.943  6014  6014 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1486-1488)
,11-08 11:43:13.943  6014  6014 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 11:43:13.952  6014  6014 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {caa1f5}
11-08 11:43:13.952  6014  6014 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 11:43:13.952  6014  6014 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-08 11:43:13.956  6014  6014 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-08 11:43:13.957  6014  6014 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-08 11:43:13.967  6014  6014 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-08 11:43:13.975  6014  6014 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-08 11:43:13.975  6014  6014 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 11:43:13.975  6014  6014 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 11:43:13.975  6014  6014 I Adreno  : Build Date                       : 12/06/15
11-08 11:43:13.975  6014  6014 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 11:43:13.975  6014  6014 I Adreno  : Local Branch                     : mybranch17112971
11-08 11:43:13.975  6014  6014 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 11:43:13.975  6014  6014 I Adreno  : Remote Branch                    : NONE
11-08 11:43:13.975  6014  6014 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 11:43:14.006   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@976b339:true
,11-08 11:43:14.016  2977  2977 W Binder_5: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[15126]" dev="sockfs" ino=15126 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:43:14.016  2977  2977 W Binder_5: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[15126]" dev="sockfs" ino=15126 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:43:14.030  6014  6014 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-08 11:43:14.038  6014  6014 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-08 11:43:14.093  2977  2977 W Binder_5: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[33974]" dev="sockfs" ino=33974 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:43:14.097  6014  6050 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-08 11:43:14.093  2977  2977 W Binder_5: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[33974]" dev="sockfs" ino=33974 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 11:43:14.096  3138  3138 W Binder_3: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[15138]" dev="sockfs" ino=15138 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:43:14.096  3138  3138 W Binder_3: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[15138]" dev="sockfs" ino=15138 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:43:14.102  6014  6037 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-08 11:43:14.147  6014  6050 I OpenGLRenderer: Initialized EGL, version 1.4
,11-08 11:43:14.158  6012  6012 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-08 11:43:14.172   929  3450 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5645 uid 10077
,11-08 11:43:14.172  6012  6012 D AndroidRuntime: CheckJNI is OFF
11-08 11:43:14.170  3450  3450 W Binder_6: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[36276]" dev="sockfs" ino=36276 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:43:14.170  3450  3450 W Binder_6: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[36276]" dev="sockfs" ino=36276 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:43:14.180  3686  3686 I Keyboard.Facilitator: onFinishInput()
,11-08 11:43:14.176  3449  3449 W Binder_5: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[36275]" dev="sockfs" ino=36275 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 11:43:14.176  3449  3449 W Binder_5: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[36275]" dev="sockfs" ino=36275 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 11:43:14.195  6012  6012 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-08 11:43:14.204   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +321ms (total +350ms)
,11-08 11:43:14.219  6012  6012 I Radio-JNI: register_android_hardware_Radio DONE
,11-08 11:43:14.233  6014  6014 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6014
,11-08 11:43:14.233  6012  6012 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-08 11:43:14.238   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-08 11:43:14.238   929   942 I ActivityManager: Killing 6014:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-08 11:43:14.263   929  3450 I WindowState: WIN DEATH: Window{d62475c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-08 11:43:14.263   929  3138 D GraphicsStats: Buffer count: 2
,11-08 11:43:14.343   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-08 11:43:14.344   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-08 11:43:14.344   929   942 E ActivityManager: Failure starting process com.test.thalitest
11-08 11:43:14.344   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-08 11:43:14.344   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:43:14.344   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:43:14.344   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 11:43:14.344   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-08 11:43:14.345   929   942 I ActivityManager:   Force finishing activity ActivityRecord{eb6d10d u0 com.test.thalitest/.MainActivity t68}
,11-08 11:43:14.346   929   952 I art     : Starting a blocking GC Explicit
,11-08 11:43:14.351   929  3138 W ActivityManager: Spurious death for ProcessRecord{50b33a 0:com.test.thalitest/u0a77}, curProc for 6014: null
,11-08 11:43:14.433   929   952 I art     : Explicit concurrent mark sweep GC freed 15392(1045KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 2.225ms total 86.459ms
,11-08 11:43:14.455   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-08 11:43:14.459  6012  6012 I art     : System.exit called, status: 0
,11-08 11:43:14.459  6012  6012 I AndroidRuntime: VM exiting with result code 0.
,11-08 11:43:14.464   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-08 11:43:14.474   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
11-08 11:43:14.476  3686  3686 I Keyboard.Facilitator: resetDictionaries() : en_US
11-08 11:43:14.479  5878  5878 D BluetoothMapAppObserver: onReceive
11-08 11:43:14.479  5878  5878 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-08 11:43:14.484   929  2975 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-08 11:43:14.485  3755  4115 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-08 11:43:14.507  3424  6063 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-08 11:43:14.510  3686  6062 I Keyboard.Facilitator.DecoderInitializer: run()
,11-08 11:43:14.538  3816  3816 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-08 11:43:14.540    29    29 W kworker/3:1: type=1400 audit(0.0:141): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 11:43:14.543    29    29 W kworker/3:1: type=1400 audit(0.0:142): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 11:43:14.553  3595  3595 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-08 11:43:14.553   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-08 11:43:14.554  3595  3595 D AndroidRuntime: Shutting down VM
11-08 11:43:14.554  3852  3932 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
--------- beginning of crash
11-08 11:43:14.554  3595  3595 E AndroidRuntime: FATAL EXCEPTION: main
11-08 11:43:14.554  3595  3595 E AndroidRuntime: Process: com.google.process.gapps, PID: 3595
11-08 11:43:14.554  3595  3595 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-08 11:43:14.554  3595  3595 E AndroidRuntime: 	... 8 more
,11-08 11:43:14.556    29    29 W kworker/3:1: type=1400 audit(0.0:143): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-08 11:43:14.562  3686  6062 I Decoder : createOrResetDecoder
11-08 11:43:14.568   929  3138 I ActivityManager: Start proc 6068:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-08 11:43:14.569  3852  3932 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-08 11:43:14.569  3852  3932 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3852
11-08 11:43:14.569  3852  3932 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-08 11:43:14.569  3852  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-08 11:43:14.569  3852  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-08 11:43:14.569  3852  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-08 11:43:14.569  3852  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-08 11:43:14.569  3852  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-08 11:43:14.569  3852  3932 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-08 11:43:14.569  3852  3932 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-08 11:43:14.569  3852  3932 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 11:43:14.569  3852  3932 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 11:43:14.569  3852  3932 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-08 11:43:14.569  3852  3932 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: Can't write: system_app_crash
11-08 11:43:14.575   929  6077 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 11:43:14.575   929  6077 E DropBoxManagerService: 	... 5 more
11-08 11:43:14.578   929  3877 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-08 11:43:14.579   929  6079 E DropBoxManagerService: Can't write: system_app_crash
11-08 11:43:14.579   929  6079 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
11-08 11:43:14.579   929  6079 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-08 11:43:14.579   929  6079 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-08 11:43:14.579   929  6079 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-08 11:43:14.579   929  6079 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-08 11:43:14.579   929  6079 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-08 11:43:14.579   929  6079 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-08 11:43:14.579   929  6079 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-08 11:43:14.579   929  6079 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-08 11:43:14.579   929  6079 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-08 11:43:14.579   929  6079 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 11:43:14.579   929  6079 E DropBoxManagerService: 	... 5 more
11-08 11:43:14.587  3595  3595 I Process : Sending signal. PID: 3595 SIG: 9
,11-08 11:43:14.588   379   379 E lowmemorykiller: Error writing /proc/3595/oom_score_adj; errno=22
11-08 11:43:14.590  3852  3932 I Process : Sending signal. PID: 3852 SIG: 9
11-08 11:43:14.599   929  2986 D WifiService: Client connection lost with reason: 4
11-08 11:43:14.610   929  3450 I ActivityManager: Process com.google.process.gapps (pid 3595) has died
11-08 11:43:14.610   929  3450 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
11-08 11:43:14.610   929  3450 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
11-08 11:43:14.610   929  3450 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 21000ms
11-08 11:43:14.611  3424  3461 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjEFCAAA9C5) - 
11-08 11:43:14.624   929  3449 I ActivityManager: Start proc 6082:com.google.process.gapps/u0a12 for service com.google.android.gms/.config.ConfigService

```
