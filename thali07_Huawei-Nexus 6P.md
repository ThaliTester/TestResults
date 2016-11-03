#### Test 91818238c75484c_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-03 12:29:01.608  3865  4262 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,11-03 12:29:02.140  5631  5631 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-03 12:29:02.146  5631  5631 D AndroidRuntime: CheckJNI is OFF
11-03 12:29:02.179  5631  5631 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-03 12:29:02.216  5631  5631 I Radio-JNI: register_android_hardware_Radio DONE
11-03 12:29:02.232  5631  5631 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-03 12:29:02.235   932  3811 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-03 12:29:02.265  3998  4008 W SearchService: Abort, client detached.
11-03 12:29:02.272  3998  3998 I HotwordDetector: Closing mic
11-03 12:29:02.272  3998  4232 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@b086221
11-03 12:29:02.272  3998  4243 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-03 12:29:02.276  5631  5631 D AndroidRuntime: Shutting down VM
11-03 12:29:02.301   932  3449 I ActivityManager: Start proc 5640:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-03 12:29:02.352   514  4249 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-03 12:29:02.354   514  4249 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-03 12:29:02.357   514  4249 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-03 12:29:02.357   514  4249 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-03 12:29:02.357   514  3026 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-03 12:29:02.361  3998  4239 I MicroRecognitionRnrImpl: Detection finished
11-03 12:29:02.362  3998  4235 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-03 12:29:02.389  5640  5640 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-03 12:29:02.407  5640  5640 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-03 12:29:02.462  5640  5640 I LibraryLoader: Time to load native libraries: 52 ms (timestamps 6689-6741)
11-03 12:29:02.462  5640  5640 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 12:29:02.489  5640  5640 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f81b9c}
11-03 12:29:02.491  5640  5640 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 12:29:02.492  5640  5640 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 12:29:02.496  5640  5640 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 12:29:02.497  5640  5640 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 12:29:02.552  5640  5640 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 12:29:02.564  5640  5640 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-03 12:29:02.564  5640  5640 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 12:29:02.564  5640  5640 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 12:29:02.564  5640  5640 I Adreno  : Build Date                       : 12/06/15
11-03 12:29:02.564  5640  5640 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 12:29:02.564  5640  5640 I Adreno  : Local Branch                     : mybranch17112971
11-03 12:29:02.564  5640  5640 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 12:29:02.564  5640  5640 I Adreno  : Remote Branch                    : NONE
11-03 12:29:02.564  5640  5640 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 12:29:02.595   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@66ae0b0:true
,11-03 12:29:02.626   408   408 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[25207]" dev="sockfs" ino=25207 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:29:02.626   408   408 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25207]" dev="sockfs" ino=25207 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:29:02.639  5640  5640 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 12:29:02.647  5640  5640 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 12:29:02.666  2610  2610 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32026]" dev="sockfs" ino=32026 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 12:29:02.666  2610  2610 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32026]" dev="sockfs" ino=32026 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 12:29:02.670  5640  5677 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 12:29:02.669  3868  3868 W Binder_B: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[25219]" dev="sockfs" ino=25219 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:29:02.669  3868  3868 W Binder_B: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[25219]" dev="sockfs" ino=25219 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 12:29:02.674  5640  5664 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-03 12:29:02.698  5640  5677 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 12:29:02.769   932   950 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +489ms
,11-03 12:29:02.766  3817  3817 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32826]" dev="sockfs" ino=32826 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 12:29:02.766  3817  3817 W Binder_A: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32826]" dev="sockfs" ino=32826 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 12:29:02.769   942   942 W Binder_1: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32825]" dev="sockfs" ino=32825 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:29:02.769   942   942 W Binder_1: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32825]" dev="sockfs" ino=32825 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 12:29:02.772  3684  3684 I Keyboard.Facilitator: onFinishInput()
,11-03 12:29:02.818  5640  5640 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5640
,11-03 12:29:02.915  5640  5640 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 12:29:03.053  5640  5680 D jxcore_app_log: JniHelper::setJavaVM(0xf543c000), pthread_self() = -562820816
,11-03 12:29:03.058  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-03 12:29:03.058  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-03 12:29:03.058  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-03 12:29:03.058  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-03 12:29:03.058  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-03 12:29:03.058  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ed5492 added. We now have 1 listener(s)
,11-03 12:29:03.060  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-03 12:29:03.061  5640  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 12:29:03.063  5640  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 12:29:03.063  5640  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-03 12:29:03.065  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3362b19 added. We now have 1 listener(s)
,11-03 12:29:03.065  5640  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 12:29:03.069   932  2991 D WifiService: New client listening to asynchronous messages
,11-03 12:29:03.070  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 12:29:03.070  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-03 12:29:03.070  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-03 12:29:03.070  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-03 12:29:03.070  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-03 12:29:03.072  5640  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 12:29:03.072  5640  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 12:29:03.075  5640  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-03 12:29:03.076  5640  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:29:03.076  5640  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:03.076  5640  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:03.076  5640  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:03.076  5640  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:03.076  5640  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:03.076  5640  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:29:03.076  5640  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 12:29:03.076  5640  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-03 12:29:03.076  5640  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 12:29:03.076  5640  5680 I io.jxcore.node.LifeCycleMonitor: start: OK
11-03 12:29:03.078  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:03.080  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:03.090  5640  5640 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-03 12:29:03.475  5640  5687 W jxcore-log: Initializing JXcore engine
,11-03 12:29:03.475  5640  5687 W jxcore-log: JXcore engine is ready
,11-03 12:29:03.502  5687  5687 W Thread-66: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11890 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-03 12:29:03.502  5687  5687 W Thread-66: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14463]" dev="sockfs" ino=14463 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-03 12:29:03.502  5687  5687 W Thread-66: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-03 12:29:03.502  5687  5687 W Thread-66: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32806]" dev="sockfs" ino=32806 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-03 12:29:03.512  5640  5687 W jxcore-log: Starting JXcore engine
,11-03 12:29:03.565  5640  5687 W jxcore-log: Platform android
11-03 12:29:03.565  5640  5687 W jxcore-log: 
11-03 12:29:03.566  5640  5687 W jxcore-log: Process ARCH arm
11-03 12:29:03.566  5640  5687 W jxcore-log: 
,11-03 12:29:03.706  5640  5687 I jxcore-log: JXcore Cordova bridge is ready!
11-03 12:29:03.706  5640  5687 I jxcore-log: 
,11-03 12:29:03.706  5640  5687 W jxcore-log: JXcore engine is started
,11-03 12:29:03.712  5640  5680 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-03 12:29:03.716  5640  5640 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-03 12:29:05.703  3607  3607 I ConfigService: onDestroy
,11-03 12:29:06.613   932  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 12:29:07.281   932  3868 I ActivityManager: Killing 5200:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-03 12:29:09.709   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:10.710   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:11.711   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:12.319   932  2968 I ActivityManager: Killing 5289:org.codeaurora.ims/1001 (adj 15): empty #17
,11-03 12:29:12.474   932  2991 D WifiService: New client listening to asynchronous messages
,11-03 12:29:12.478  3998  5689 W CronetSyncConnectionRcs: Upload content type not set.
,11-03 12:29:12.711   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:13.603  5640  5687 I jxcore-log: 2016-11-03 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-03 12:29:13.603  5640  5687 I jxcore-log: 
,11-03 12:29:13.605  5640  5687 I jxcore-log: 2016-11-03 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-03 12:29:13.605  5640  5687 I jxcore-log: 
,11-03 12:29:13.614  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:29:13.614  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:13.614  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:13.614  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:13.614  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:13.614  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:13.614  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:29:13.614  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 12:29:13.616  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 12:29:13.618  5640  5687 I jxcore-log: 2016-11-03 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-03 12:29:13.618  5640  5687 I jxcore-log: 
,11-03 12:29:13.619  5640  5687 I jxcore-log: 2016-11-03 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-03 12:29:13.619  5640  5687 I jxcore-log: 
,11-03 12:29:13.712   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:13.886  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 12:29:13.886  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fb87f added. We now have 2 listener(s)
11-03 12:29:13.887  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:29:13.887  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 12:29:13.887  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 12:29:13.887  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 12:29:13.887  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@692704c added. We now have 2 listener(s)
11-03 12:29:13.887  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 12:29:13.888  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 12:29:13.890  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 12:29:13.893  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:29:13.893  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:13.893  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:13.893  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:13.893  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:13.893  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:13.893  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:29:13.893  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 12:29:13.894  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:13.894  5640  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 12:29:13.895  5640  5687 D ExecuteNativeTests: Running unit tests
11-03 12:29:13.895  5640  5687 D BluetoothAdapter: enable(): BT is already enabled..!
,11-03 12:29:13.896   932  3873 D WifiService: setWifiEnabled: true pid=5640, uid=10077
11-03 12:29:13.896   932  3873 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:29:13.900  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:13.906  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:14.713   570   570 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 12:29:15.345  4903  4960 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-03 12:29:15.347  4903  4903 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-03 12:29:23.906  5640  5687 I com.test.thalitest.ThaliTestRunner: Running UT
,11-03 12:29:23.972  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 12:29:23.972  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@641aafe added. We now have 3 listener(s)
11-03 12:29:23.973  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 12:29:23.973  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 12:29:23.973  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 12:29:23.974  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 12:29:23.974  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a83625f added. We now have 3 listener(s)
,11-03 12:29:23.974  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 12:29:23.975  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 12:29:23.978  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:29:23.982  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:29:23.982  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:23.982  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:23.982  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:23.982  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:23.982  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:23.982  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:29:23.982  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 12:29:23.983  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:23.984  5640  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 12:29:23.989  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-03 12:29:23.989  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 12:29:23.989  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:29:23.989  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:29:23.989  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:29:23.990  5640  5687 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-03 12:29:23.990  5640  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 12:29:23.990  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 12:29:23.990  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:29:23.990  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 12:29:23.990  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:29:23.991  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-03 12:29:23.991  5640  5687 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-03 12:29:23.992  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-03 12:29:23.994  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-03 12:29:23.994  5640  5687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-03 12:29:23.998  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:24.002  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:24.003  5640  5687 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-03 12:29:24.003  5640  5687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-03 12:29:24.003  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-03 12:29:24.003  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-03 12:29:24.004  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-03 12:29:24.004  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 12:29:24.004  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:29:24.004  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-03 12:29:24.005  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 12:29:24.005  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-03 12:29:24.005  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 12:29:24.005  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 12:29:24.005  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-03 12:29:24.006  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 12:29:24.006  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 12:29:24.006  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-03 12:29:24.006  5640  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 12:29:24.008  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:29:24.008  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:29:24.008  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 12:29:24.008  5640  5702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:29:24.012  5640  5702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-03 12:29:24.009  4694  4694 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32045]" dev="sockfs" ino=32045 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 12:29:24.009  4694  4694 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32045]" dev="sockfs" ino=32045 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 12:29:24.013  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 12:29:24.015  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:29:24.015  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 12:29:24.017  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.017  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:29:24.017  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:29:24.017  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-03 12:29:24.018  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:29:24.018  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.018  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.018  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.018  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.018  5640  5687 D BluetoothAdapter: STATE_ON
,11-03 12:29:24.021  4682  4938 D BtGatt.GattService: registerClient() - UUID=54434dbd-0cd8-4fd4-8744-5d755ce191d3
,11-03 12:29:24.022  4682  4768 D BtGatt.GattService: onClientRegistered() - UUID=54434dbd-0cd8-4fd4-8744-5d755ce191d3, clientIf=5
,11-03 12:29:24.023  5640  5679 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-03 12:29:24.025  4682  4770 D BtGatt.AdvertiseManager: message : 0
,11-03 12:29:24.027  4682  4770 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:29:24.043  4682  4768 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:29:24.050  4682  4768 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:29:24.052  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.052  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.052  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:29:24.052  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.052  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.052  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.052  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.053  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.053  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-03 12:29:24.053  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-03 12:29:24.055  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.055  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.056  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.056  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.056  5640  5687 I io.jxcore.node.ConnectionHelper: start: OK
,11-03 12:29:24.056  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-03 12:29:24.057  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.057  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:24.057  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-03 12:29:24.057  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.057  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-03 12:29:24.058  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.058  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:29:24.058  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:29:24.058  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.058  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.058  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-03 12:29:24.058  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.062  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.062  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-03 12:29:24.062  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-03 12:29:24.062  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.062  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.063  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:24.063  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-03 12:29:24.559  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 12:29:24.560  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-03 12:29:24.560  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 12:29:24.560  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 12:29:24.560  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 12:29:24.560  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-03 12:29:24.560  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 12:29:24.560  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 12:29:24.560  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 12:29:24.560  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 12:29:24.560  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 12:29:24.561  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 12:29:24.561  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-03 12:29:24.561  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 12:29:24.561  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 12:29:24.561  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 12:29:24.561  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 12:29:24.561  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 12:29:24.561  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 12:29:24.562  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 12:29:24.562  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 12:29:24.562  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 12:29:24.562  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 12:29:24.562  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 12:29:24.562  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 12:29:24.562  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 12:29:24.562  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-03 12:29:24.562  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 12:29:24.563  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 12:29:24.563  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 12:29:24.563  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 12:29:24.563  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-03 12:29:24.563  5640  5687 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 12:29:24.563  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-03 12:29:24.563  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 12:29:24.563  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 12:29:24.563  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 12:29:24.563  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 12:29:24.564  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-03 12:29:24.564  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-03 12:29:24.565  5640  5702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 12:29:24.565  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 12:29:24.565  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 12:29:24.565  5640  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 12:29:24.566  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 12:29:24.566  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 12:29:24.566  5640  5702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 12:29:24.566  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-03 12:29:24.566  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 12:29:24.567  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.567  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.568  5640  5687 D BluetoothAdapter: STATE_ON
11-03 12:29:24.568  5640  5687 D BluetoothLeScanner: could not find callback wrapper
11-03 12:29:24.569  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-03 12:29:24.569  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.569  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.569  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-03 12:29:24.569  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.570  4682  4770 D BtGatt.AdvertiseManager: message : 1
11-03 12:29:24.572  4682  4770 D BtGatt.AdvertiseManager: stop advertise for client 5
11-03 12:29:24.584  4682  4768 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-03 12:29:24.585  4682  4768 D BtGatt.GattService: Client app is not null!
,11-03 12:29:24.586  4682  4937 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 12:29:24.587  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-03 12:29:24.587  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.587  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-03 12:29:24.588  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.588  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.588  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.588  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 12:29:24.588  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:29:24.589  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.589  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.589  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-03 12:29:24.589  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.591  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.592  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:29:24.592  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.592  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.592  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.592  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.593  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.593  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 12:29:24.594  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-03 12:29:24.598  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 12:29:24.598  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.600  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.600  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.600  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.600  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 12:29:24.601  5640  5640 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-03 12:29:24.601  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 12:29:24.602  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:29:24.602  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 12:29:24.602  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 12:29:24.602  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:29:24.602  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:29:24.602  5640  5687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-03 12:29:24.602  5640  5687 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-03 12:29:24.603  5640  5687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-03 12:29:24.603  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-03 12:29:24.603  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-03 12:29:24.603  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-03 12:29:24.603  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 12:29:24.603  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:29:24.604  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-03 12:29:24.605  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 12:29:24.605  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 12:29:24.605  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 12:29:24.606  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 12:29:24.606  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-03 12:29:24.606  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-03 12:29:24.606  5640  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 12:29:24.606  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 12:29:24.606  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 12:29:24.608  5640  5705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:29:24.609  4937  4937 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32053]" dev="sockfs" ino=32053 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 12:29:24.609  4937  4937 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32053]" dev="sockfs" ino=32053 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 12:29:24.611  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 12:29:24.611  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:29:24.611  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 12:29:24.612  5640  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-03 12:29:24.616  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 12:29:24.617  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:29:24.617  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 12:29:24.620  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.620  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:29:24.620  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:29:24.620  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
,11-03 12:29:24.620  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:29:24.620  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.621  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.621  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.621  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.622  5640  5687 D BluetoothAdapter: STATE_ON
,11-03 12:29:24.625  4682  4694 D BtGatt.GattService: registerClient() - UUID=26e363f8-a39b-4aca-9594-599e7a620476
11-03 12:29:24.626  4682  4768 D BtGatt.GattService: onClientRegistered() - UUID=26e363f8-a39b-4aca-9594-599e7a620476, clientIf=5
,11-03 12:29:24.626  5640  5650 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-03 12:29:24.627  4682  4770 D BtGatt.AdvertiseManager: message : 0
,11-03 12:29:24.630  4682  4770 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:29:24.643  4682  4768 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:29:24.651  4682  4768 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:29:24.651  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.651  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.652  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:29:24.652  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.652  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.652  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.652  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.652  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.652  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 12:29:24.654  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:29:24.654  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.656  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:24.656  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.656  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:24.657  5640  5687 I io.jxcore.node.ConnectionHelper: start: OK
11-03 12:29:24.657  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-03 12:29:24.657  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-03 12:29:24.657  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:24.657  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-03 12:29:24.657  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.657  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:24.657  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.657  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-03 12:29:24.657  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:29:24.658  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.658  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.658  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-03 12:29:24.658  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.661  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.661  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-03 12:29:24.661  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.661  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.661  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:29:24.661  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:24.662  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-03 12:29:25.161  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-03 12:29:25.162  5640  5687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-03 12:29:25.162  5640  5687 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-03 12:29:25.162  5640  5687 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 12:29:25.162  5640  5687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-03 12:29:25.162  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-03 12:29:25.163  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-03 12:29:25.163  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-03 12:29:25.163  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-03 12:29:25.163  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-03 12:29:25.163  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-03 12:29:25.163  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-03 12:29:25.163  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-03 12:29:25.163  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-03 12:29:25.163  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-03 12:29:25.163  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-03 12:29:25.163  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:25.165  4682  4770 D BtGatt.AdvertiseManager: message : 1
11-03 12:29:25.167  4682  4770 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-03 12:29:25.181  4682  4768 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-03 12:29:25.181  4682  4768 D BtGatt.GattService: Client app is not null!
,11-03 12:29:25.182  4682  4937 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 12:29:25.183  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 12:29:25.183  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.183  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-03 12:29:25.183  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:25.184  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.185  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 12:29:25.185  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.185  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:29:25.185  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:29:25.185  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-03 12:29:25.186  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:29:25.186  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.186  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.186  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.186  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:25.190  5640  5687 D BluetoothAdapter: STATE_ON
,11-03 12:29:25.195  4682  4937 D BtGatt.GattService: registerClient() - UUID=05c67a83-e4ef-4ec3-9e9e-696a0879ca94
,11-03 12:29:25.196  4682  4768 D BtGatt.GattService: onClientRegistered() - UUID=05c67a83-e4ef-4ec3-9e9e-696a0879ca94, clientIf=5
,11-03 12:29:25.196  5640  5650 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-03 12:29:25.198  4682  4770 D BtGatt.AdvertiseManager: message : 0
,11-03 12:29:25.202  4682  4770 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:29:25.218  4682  4768 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:29:25.225  4682  4768 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:29:25.226  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.226  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.226  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-03 12:29:25.226  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.226  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.226  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.226  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:25.227  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.227  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-03 12:29:25.227  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 12:29:25.227  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-03 12:29:25.227  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 12:29:25.227  5640  5687 I io.jxcore.node.ConnectionHelper: start: OK
11-03 12:29:25.227  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.228  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-03 12:29:25.228  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-03 12:29:25.228  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.228  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:25.228  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.228  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:29:25.228  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 12:29:25.228  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:29:25.228  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-03 12:29:25.228  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.228  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 12:29:25.229  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.229  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 12:29:25.229  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:25.229  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 12:29:25.229  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 12:29:25.229  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-03 12:29:25.229  5640  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 12:29:25.229  5640  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 12:29:25.229  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 12:29:25.229  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 12:29:25.229  5640  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 12:29:25.229  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 12:29:25.229  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 12:29:25.229  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 12:29:25.229  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 12:29:25.229  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 12:29:25.229  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.230  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.231  5640  5687 D BluetoothAdapter: STATE_ON
11-03 12:29:25.231  5640  5687 D BluetoothLeScanner: could not find callback wrapper
11-03 12:29:25.231  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 12:29:25.231  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.231  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.231  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-03 12:29:25.231  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.232  4682  4770 D BtGatt.AdvertiseManager: message : 1
11-03 12:29:25.233  4682  4770 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-03 12:29:25.241  4682  4768 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-03 12:29:25.241  4682  4768 D BtGatt.GattService: Client app is not null!
11-03 12:29:25.242  4682  4937 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 12:29:25.242  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-03 12:29:25.242  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.242  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-03 12:29:25.242  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.242  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 12:29:25.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:29:25.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.243  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-03 12:29:25.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.245  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.245  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:29:25.245  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.245  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.245  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.245  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.245  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.245  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 12:29:25.245  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-03 12:29:25.247  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 12:29:25.247  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.248  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.248  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.248  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.249  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 12:29:25.249  5640  5640 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-03 12:29:25.249  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 12:29:25.249  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 12:29:25.249  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:29:25.249  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:29:25.249  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:29:25.251  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-03 12:29:25.251  5640  5687 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-03 12:29:25.252  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-03 12:29:25.253  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-03 12:29:25.254  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-03 12:29:25.254  5640  5687 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-03 12:29:25.255  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-03 12:29:25.255  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-03 12:29:25.256  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-03 12:29:25.256  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 12:29:25.256  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:29:25.256  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:29:25.256  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:29:25.256  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 12:29:25.256  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:29:25.256  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:29:25.257  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:29:25.257  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 12:29:25.257  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:29:25.257  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:29:25.257  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:29:25.258  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-03 12:29:25.258  5640  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 12:29:25.258  5640  5687 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-03 12:29:25.261  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,11-03 12:29:25.261  5640  5687 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-03 12:29:25.262  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-03 12:29:25.263  5640  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-03 12:29:25.263  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-03 12:29:25.264  5640  5687 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-03 12:29:25.264  5640  5687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-03 12:29:25.264  5640  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-03 12:29:25.264  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 12:29:25.264  5640  5687 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-03 12:29:25.264  5640  5687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 12:29:25.264  5640  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-03 12:29:25.264  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 12:29:25.264  5640  5687 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-03 12:29:25.264  5640  5687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 12:29:25.264  5640  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 12:29:25.264  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 12:29:25.264  5640  5687 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-03 12:29:25.265  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
,11-03 12:29:25.265  5640  5687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-03 12:29:25.265  5640  5687 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-03 12:29:25.265  5640  5687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-03 12:29:25.265  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-03 12:29:25.266  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-03 12:29:25.266  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-03 12:29:25.266  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 12:29:25.266  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:29:25.266  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-03 12:29:25.267  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-03 12:29:25.267  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 12:29:25.267  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 12:29:25.267  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 12:29:25.267  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-03 12:29:25.267  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:29:25.267  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 12:29:25.267  5640  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 12:29:25.268  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-03 12:29:25.270  5640  5709 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:29:25.272  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:29:25.272  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:29:25.269  4695  4695 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33941]" dev="sockfs" ino=33941 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 12:29:25.269  4695  4695 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33941]" dev="sockfs" ino=33941 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 12:29:25.273  5640  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-03 12:29:25.279  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 12:29:25.279  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:29:25.279  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 12:29:25.281  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.281  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-03 12:29:25.281  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:29:25.282  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-03 12:29:25.282  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:29:25.282  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.282  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.282  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.282  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.282  5640  5687 D BluetoothAdapter: STATE_ON
11-03 12:29:25.285  4682  4695 D BtGatt.GattService: registerClient() - UUID=16daba6d-ecdc-4453-bc1d-79020fbcb55e
,11-03 12:29:25.285  4682  4768 D BtGatt.GattService: onClientRegistered() - UUID=16daba6d-ecdc-4453-bc1d-79020fbcb55e, clientIf=5
11-03 12:29:25.286  5640  5651 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-03 12:29:25.287  4682  4770 D BtGatt.AdvertiseManager: message : 0
11-03 12:29:25.289  4682  4770 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:29:25.299  4682  4768 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:29:25.305  4682  4768 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:29:25.305  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.306  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.306  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-03 12:29:25.306  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.306  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.306  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.306  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.306  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.306  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 12:29:25.307  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:29:25.307  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:25.308  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.309  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.309  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.309  5640  5687 I io.jxcore.node.ConnectionHelper: start: OK
11-03 12:29:25.309  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-03 12:29:25.309  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.309  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:25.309  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-03 12:29:25.309  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.309  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:25.309  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.309  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:29:25.310  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:29:25.310  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.310  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.310  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-03 12:29:25.310  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.312  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.312  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-03 12:29:25.312  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.312  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.312  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:29:25.312  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:25.312  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-03 12:29:25.811  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 12:29:25.811  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 12:29:25.811  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 12:29:25.811  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 12:29:25.811  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-03 12:29:25.812  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-03 12:29:25.812  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 12:29:25.812  5640  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 12:29:25.812  5640  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 12:29:25.812  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-03 12:29:25.812  5640  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 12:29:25.812  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@641aafe removed from the list
11-03 12:29:25.813  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 12:29:25.813  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-03 12:29:25.813  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 12:29:25.813  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 12:29:25.813  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.813  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-03 12:29:25.813  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:25.814  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 12:29:25.814  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 12:29:25.814  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 12:29:25.816  5640  5687 D BluetoothAdapter: STATE_ON
11-03 12:29:25.817  5640  5687 D BluetoothLeScanner: could not find callback wrapper
,11-03 12:29:25.817  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 12:29:25.818  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.818  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.818  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-03 12:29:25.818  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.821  4682  4770 D BtGatt.AdvertiseManager: message : 1
11-03 12:29:25.823  4682  4770 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-03 12:29:25.833  4682  4768 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-03 12:29:25.833  4682  4768 D BtGatt.GattService: Client app is not null!
,11-03 12:29:25.834  4682  4694 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 12:29:25.835  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 12:29:25.835  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.835  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-03 12:29:25.835  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.836  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:25.836  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.836  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 12:29:25.836  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:29:25.836  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.836  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.836  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-03 12:29:25.836  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.838  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.838  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:29:25.838  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.838  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:25.838  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.838  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.839  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.839  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 12:29:25.839  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 12:29:25.839  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 12:29:25.839  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.841  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.841  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.841  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:25.841  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a83625f removed from the list
11-03 12:29:25.841  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 12:29:25.842  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 12:29:25.842  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:29:25.842  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:29:25.842  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 12:29:26.343  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 12:29:30.845  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
11-03 12:29:30.847  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 12:29:30.848  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 12:29:30.850  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-03 12:29:30.851  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-03 12:29:30.851  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-03 12:29:30.855  4694  4694 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[34848]" dev="sockfs" ino=34848 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 12:29:30.855  4694  4694 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[34848]" dev="sockfs" ino=34848 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 12:29:30.851  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 12:29:30.852  5640  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 12:29:30.852  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-03 12:29:30.852  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 12:29:30.852  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-03 12:29:30.853  5640  5710 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:29:30.856  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-03 12:29:30.858  5640  5687 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-03 12:29:30.858  5640  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 12:29:30.859  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 12:29:30.859  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:29:30.859  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:29:30.860  5640  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-03 12:29:30.863  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-03 12:29:30.870  5640  5687 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-03 12:29:30.871  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 12:29:30.871  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 12:29:30.871  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 12:29:30.871  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-03 12:29:30.871  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 12:29:30.871  5640  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 12:29:30.871  5640  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 12:29:30.871  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-03 12:29:30.871  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 12:29:30.871  5640  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 12:29:30.871  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@641aafe not in the list
11-03 12:29:30.871  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-03 12:29:30.872  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 12:29:30.872  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 12:29:30.872  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 12:29:30.872  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 12:29:30.872  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 12:29:30.872  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 12:29:30.872  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 12:29:30.872  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 12:29:30.872  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:30.875  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:30.875  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:29:30.875  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:30.875  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:30.875  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a83625f not in the list
11-03 12:29:30.875  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:29:30.875  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-03 12:29:30.875  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 12:29:30.875  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-03 12:29:30.875  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 12:29:30.875  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 12:29:30.877  5640  5687 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-03 12:29:30.878  5640  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-03 12:29:30.878  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 12:29:30.878  5640  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-03 12:29:30.878  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 12:29:30.878  5640  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-03 12:29:30.878  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-03 12:29:30.879  5640  5687 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-03 12:29:30.880  5640  5687 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-03 12:29:30.881  5640  5687 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-03 12:29:30.881  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 12:29:30.882  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-03 12:29:30.882  5640  5687 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,11-03 12:29:30.882  5640  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-03 12:29:30.882  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 12:29:30.883  5640  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-03 12:29:30.883  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 12:29:30.883  5640  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-03 12:29:30.883  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-03 12:29:30.884  5640  5687 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-03 12:29:30.884  5640  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-03 12:29:30.884  5640  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-03 12:29:30.885  5640  5687 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-03 12:29:30.885  5640  5687 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-03 12:29:30.885  5640  5687 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-03 12:29:30.885  5640  5687 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-03 12:29:30.885  5640  5687 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-03 12:29:30.886  5640  5687 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-03 12:29:30.886  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 12:29:30.886  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6fa14f added. We now have 3 listener(s)
,11-03 12:29:30.888  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 12:29:30.888  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 12:29:30.888  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 12:29:30.888  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 12:29:30.888  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7f0dc added. We now have 3 listener(s)
11-03 12:29:30.888  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 12:29:30.889  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 12:29:30.892  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 12:29:30.895  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:29:30.895  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:30.895  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:30.895  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:30.895  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:30.895  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:30.895  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:29:30.895  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 12:29:30.897  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:30.897  5640  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 12:29:30.898  5640  5687 D BluetoothAdapter: enable(): BT is already enabled..!
11-03 12:29:30.899   932   943 D WifiService: setWifiEnabled: true pid=5640, uid=10077
11-03 12:29:30.899   932   943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-03 12:29:30.899  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:30.900  5640  5687 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
11-03 12:29:30.902  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:30.903  5640  5687 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-03 12:29:30.903  5640  5687 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-03 12:29:30.906   932  3756 D WifiService: setWifiEnabled: false pid=5640, uid=10077
,11-03 12:29:30.906   932  3756 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:29:30.910   932  2981 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-03 12:29:30.910   932  2981 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-03 12:29:30.911   932  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 12:29:30.911   932  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 12:29:30.920   932  5418 D DhcpClient: Clearing IP address
11-03 12:29:30.920   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-03 12:29:30.928   509   925 D CommandListener: Setting iface cfg
,11-03 12:29:30.929   932  5419 D DhcpClient: Receive thread stopped
,11-03 12:29:30.934  3607  5470 V NativeCrypto: Read error: ssl=0x7f72d82380: I/O error during system call, Connection timed out
,11-03 12:29:30.936  3607  5470 V NativeCrypto: SSL shutdown failed: ssl=0x7f72d82380: I/O error during system call, Broken pipe
11-03 12:29:30.938   932  3787 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-03 12:29:30.939   932  5416 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-03 12:29:30.945   932  5416 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-03 12:29:30.948   932   932 D RttService: SCAN_AVAILABLE : 1
11-03 12:29:30.948   932  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-03 12:29:30.948   932  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,11-03 12:29:30.948   932  3102 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 12:29:30.948   932  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-03 12:29:30.950   932  2996 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-03 12:29:30.950   567   567 E Parcel  : Reading a NULL string not supported here.
11-03 12:29:30.950   932  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-03 12:29:30.957   932  2996 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-03 12:29:30.958  3747  3902 W QCNEJ   : |CORE| network lost: 100
,11-03 12:29:30.959  3747  3902 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-03 12:29:30.961   932  3868 I ActivityManager: Killing 5308:com.android.settings/1000 (adj 15): empty #17
,11-03 12:29:30.978   932  2981 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-03 12:29:30.982   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 12:29:30.999   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 12:29:30.999   509   925 D TetherController: Setting IP forward enable = 0
,11-03 12:29:31.000   932  2996 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-03 12:29:31.000   932  2996 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 12:29:31.003   932  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 12:29:31.005   932   949 D Tethering: MasterInitialState.processMessage what=3
,11-03 12:29:31.009  5322  5322 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a83ca48 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-03 12:29:31.012  3865  3865 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 12:29:31.014  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:31.014  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:31.014  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:31.014  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:31.014  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:31.014  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:31.014  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:31.014  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:31.014  3998  3998 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-03 12:29:31.015  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:31.019  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:31.019  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:31.019  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:31.019  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:31.019  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:31.019  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:31.019  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:31.019  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:31.021  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:31.021  3865  3865 D SystemUpdateService: onCreate
11-03 12:29:31.023  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:31.023  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:31.023  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:31.023  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:31.023  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:31.023  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:31.023  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:31.023  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:31.025  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:31.026  3865  3865 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 12:29:31.030  3865  5726 I SystemUpdateService: active receiver: enabled
11-03 12:29:31.033  3865  3865 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-03 12:29:31.040  3865  4336 I iu.UploadsManager: num queued entries: 0
11-03 12:29:31.040  3865  4336 I iu.UploadsManager: num updated entries: 0
,11-03 12:29:31.041  3865  3865 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 12:29:31.043  3865  3865 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 12:29:31.045  5446  5446 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 12:29:31.049  5446  5446 D SprintDMHelper: simOperator: 
,11-03 12:29:31.049  5446  5446 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 12:29:31.053   509   925 E Netd    : netlink response contains error (No such file or directory)
,11-03 12:29:31.053   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-03 12:29:31.054   509   925 D TetherController: Setting IP forward enable = 0
11-03 12:29:31.054   932  2996 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 12:29:31.056   932  2981 D DhcpClient: doQuit
11-03 12:29:31.056   932  2981 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 12:29:31.056   932  5418 D DhcpClient: onQuitting
,11-03 12:29:31.056  3865  5726 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-03 12:29:31.057  3481  3481 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-03 12:29:31.059  3865  4336 I iu.SyncManager: NEXT; no task
11-03 12:29:31.062  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:31.062  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:31.062  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:31.062  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:29:31.062  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:31.062  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:31.062  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:31.062  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:31.063  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:31.064  3865  5726 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-03 12:29:31.064  3865  5726 I SystemUpdateService: now status is 0 (complete)
11-03 12:29:31.064  3865  5726 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 12:29:31.064  3865  5726 I SystemUpdateService: file has been verified
11-03 12:29:31.064  3865  5726 I SystemUpdateService: OTA package size = 21989297
11-03 12:29:31.066  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:31.066  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:31.066  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:31.066  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:29:31.066  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:31.066  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:31.066  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:31.066  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:31.068  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:31.069  3865  5726 I SystemUpdateService: showing system update notification
,11-03 12:29:31.071  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:31.071  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:31.071  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:31.071  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:29:31.071  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:31.071  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:31.071  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:31.071  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:31.073  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:31.078  3481  3481 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 12:29:31.081   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 12:29:31.083  3481  3481 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 12:29:31.089   932  3880 I ActivityManager: Start proc 5736:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-03 12:29:31.092  3865  3865 D SystemUpdateService: onDestroy
,11-03 12:29:31.119  5736  5736 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-03 12:29:31.125   932  3868 I ActivityManager: Killing 5106:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-03 12:29:31.128  3481  3481 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 12:29:31.146  3481  3481 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 12:29:31.250   932  2981 D wifi    : In wifi stop Hal
,11-03 12:29:31.250   932  2981 D wifi    : halHandle = 0x7f71620e00, mVM = 0x7f8dc0d140, mCls = 0x100a02
,11-03 12:29:31.250   932  3480 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 12:29:31.250   932  3480 D WifiHAL : Got a signal to exit!!!
11-03 12:29:31.250   932  3480 I WifiHAL : Exit wifi_event_loop
11-03 12:29:31.250   932  2981 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-03 12:29:31.251   932  2981 E WifiHAL : Event processing terminated
11-03 12:29:31.251   932  2981 D wifi    : In wifi cleaned up handler
11-03 12:29:31.251   932  2981 I WifiHAL : Internal cleanup completed
11-03 12:29:31.254  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:31.255  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 12:29:31.256  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:31.257  4086  4252 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 12:29:31.259  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:31.277   932  3480 D wifi    : set interface wlan0 flags (DOWN)
,11-03 12:29:31.278   932  2981 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 12:29:31.375  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 12:29:31.414  5640  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:31.417   932  3868 D WifiService: setWifiEnabled: true pid=5640, uid=10077
11-03 12:29:31.417   932  3868 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:29:31.482   509   925 D SoftapController: Softap fwReload - Ok
,11-03 12:29:31.488   509   925 D CommandListener: Setting iface cfg
11-03 12:29:31.488   509   925 D CommandListener: Trying to bring down wlan0
,11-03 12:29:31.489   932   949 D Tethering: InitialState.processMessage what=4
11-03 12:29:31.490   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-03 12:29:31.495   932  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 12:29:31.497   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 12:29:31.922   932  3811 D WifiService: setWifiEnabled: true pid=5640, uid=10077
,11-03 12:29:31.924   932  3811 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:29:32.101   932  2981 D wifi    : set interface wlan0 flags (UP)
,11-03 12:29:32.101   932  2981 I WifiHAL : Initializing wifi
,11-03 12:29:32.102   932  2981 I WifiHAL : Creating socket
,11-03 12:29:32.110   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-03 12:29:32.111   932  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-03 12:29:32.112   932  2981 D wifi    : Did set static halHandle = 0x7f71620e00
,11-03 12:29:32.112   932  2981 D wifi    : halHandle = 0x7f71620e00, mVM = 0x7f8dc0d140, mCls = 0x101576
,11-03 12:29:32.112   932  2981 D wifi    : array field set
11-03 12:29:32.113   932  2981 I WifiNative-HAL: interface[0] = wlan0
,11-03 12:29:32.115   932  5751 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547363098112
,11-03 12:29:32.115   932  5751 D wifi    : waitForHalEvents called, vm = 0x7f8dc0d140, obj = 0x101576, env = 0x7f724a0740
11-03 12:29:32.122   932  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 12:29:32.130  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:32.132  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:32.135  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:32.182  5752  5752 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 12:29:32.242  5752  5752 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 12:29:32.306  5752  5752 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 12:29:32.306  5752  5752 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 12:29:32.327   932  2981 D WifiConfigStore: Loading config and enabling all networks 
,11-03 12:29:32.341  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:32.341  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:32.341  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:32.341  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:32.341  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:32.341  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:32.341  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:32.341  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:32.347  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:32.349   932  2981 D WifiConfigStore: loaded 0 passpoint configs
,11-03 12:29:32.349   932  2981 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 12:29:32.350   932  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-03 12:29:32.350   932  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-03 12:29:32.350   932  2981 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-03 12:29:32.351   932  2981 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-03 12:29:32.351   932  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-03 12:29:32.352   932  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 12:29:32.352   932  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 12:29:32.352   932  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-03 12:29:32.352   932  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-03 12:29:32.352   932  2981 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-03 12:29:32.352   932  2981 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-03 12:29:32.354   932  2981 D WifiNative-HAL: Setting external_sim to 1
11-03 12:29:32.354   932  2981 D wifi    : setting dfs flag to true, 0x7f77f57280
11-03 12:29:32.354   932  2981 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 12:29:32.355   932  2981 D wifi    : setting scan oui 0x7f77f57280
,11-03 12:29:32.355   932  2981 D WifiHAL : Sending mac address OUI
,11-03 12:29:32.355  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 12:29:32.357  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:32.357  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:32.357  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:32.357  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:32.357  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:32.357  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:32.357  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:32.357  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:32.357   932  2981 E native  : do suspend false
,11-03 12:29:32.361  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:32.364   932  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-03 12:29:32.365   932   932 D RttService: SCAN_AVAILABLE : 3
11-03 12:29:32.365   932  3102 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-03 12:29:32.365   509   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-03 12:29:32.367   509   925 D CommandListener: Setting iface cfg
11-03 12:29:32.369   932  2977 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
,11-03 12:29:32.370  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:32.370  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:32.370  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:32.370  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:32.370  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:32.370  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:32.370  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:32.370  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:32.370   932  2977 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 12:29:32.373  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:32.379   932  2977 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 12:29:32.380   932  2977 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 12:29:32.404   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=106684 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=35 mControllerEnergyUsed=133 }
,11-03 12:29:32.427  5640  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:32.433  4682  4764 D BluetoothAdapterState: Current state: ON, message: 23
,11-03 12:29:32.433  4682  4764 D BluetoothAdapterProperties: Setting state to 13
11-03 12:29:32.433  4682  4764 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-03 12:29:32.434  4682  4764 D BluetoothAdapterProperties: onBluetoothDisable()
,11-03 12:29:32.436  4682  4682 D BluetoothMapService: onReceive
,11-03 12:29:32.436  4682  4682 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-03 12:29:32.436  4682  4682 D BluetoothMapService: STATE_TURNING_OFF
11-03 12:29:32.436  4682  4682 D BluetoothMapService: MAP Service closeService in
11-03 12:29:32.436  4682  4682 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 12:29:32.436  4682  4682 D ObexServerSockets0: shutdown(block = true)
11-03 12:29:32.437  4682  4682 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 12:29:32.437  4682  4940 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-03 12:29:32.438  4682  4682 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 12:29:32.438  4682  4941 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 12:29:32.439  4682  4911 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-03 12:29:32.439  4682  4764 I BluetoothAdapterState: Entering PendingCommandState
11-03 12:29:32.442  4682  4682 I BtOppRfcommListener: stopping Accept Thread
11-03 12:29:32.442  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:29:32.442  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:32.442  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:32.442  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:32.442  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:32.442  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:29:32.442  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:32.442  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:32.442  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:32.442  4682  5349 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 12:29:32.444  4682  5349 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-03 12:29:32.444  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:29:32.445  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:32.447  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:29:32.447  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:32.447  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:32.447  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:32.447  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:32.447  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:29:32.447  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:32.447  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:32.447  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:32.448  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 12:29:32.448  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:32.450  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:29:32.450  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:32.450  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:32.450  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:32.450  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:32.450  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:29:32.450  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:32.450  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:32.450  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:32.451  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:29:32.451  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:32.453   932   945 I ActivityManager: Start proc 5756:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-03 12:29:32.454  4682  4768 D BluetoothAdapterProperties: Scan Mode:20
11-03 12:29:32.454  4682  4764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-03 12:29:32.458  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:32.461  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:32.461  4682  4682 D HeadsetService: Received stop request...Stopping profile...
11-03 12:29:32.463  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:32.464  3770  3810 D BluetoothHeadset: Proxy object disconnected
11-03 12:29:32.464   932   932 D BluetoothHeadset: Proxy object disconnected
11-03 12:29:32.465  3174  3189 D BluetoothHeadset: Proxy object disconnected
11-03 12:29:32.465   932   932 D BluetoothHeadset: Proxy object disconnected
11-03 12:29:32.465   932   932 D BluetoothHeadset: Proxy object disconnected
,11-03 12:29:32.465  4682  4682 D A2dpService: Received stop request...Stopping profile...
11-03 12:29:32.465  4682  4931 D A2dpStateMachine: Exit Disconnected: -1
,11-03 12:29:32.467   932   932 D BluetoothA2dp: Proxy object disconnected
,11-03 12:29:32.468  4682  4682 D HidService: Received stop request...Stopping profile...
11-03 12:29:32.470  4682  4682 D HidService: Stopping Bluetooth HidService
,11-03 12:29:32.471  4682  4682 D HealthService: Received stop request...Stopping profile...
,11-03 12:29:32.473  4682  4682 D PanService: Received stop request...Stopping profile...
11-03 12:29:32.474  4682  4682 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:32.474  4682  4682 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:32.474  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:32.474  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:32.474  4682  4682 D BluetoothMapService: Received stop request...Stopping profile...
11-03 12:29:32.475  4682  4682 D BluetoothMapService: stop()
11-03 12:29:32.475  3174  3174 D HeadsetProfile: Bluetooth service disconnected
11-03 12:29:32.475  3174  3174 D BluetoothA2dp: Proxy object disconnected
11-03 12:29:32.475  3174  3174 D BluetoothInputDevice: Proxy object disconnected
11-03 12:29:32.475  3174  3174 D HidProfile: Bluetooth service disconnected
11-03 12:29:32.475  4682  4682 D BluetoothMapAppObserver: deinitObservers()
,11-03 12:29:32.475  3174  3174 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 12:29:32.475  4682  4682 D BluetoothMapAppObserver: removeReceiver()
11-03 12:29:32.475  3174  3174 D PanProfile: Bluetooth service disconnected
11-03 12:29:32.479  3174  3174 D BluetoothMap: Proxy object disconnected
11-03 12:29:32.479  3174  3174 D MapProfile: Bluetooth service disconnected
11-03 12:29:32.479  4682  4682 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 12:29:32.479  4682  4682 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 12:29:32.479  4682  4768 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-03 12:29:32.480  4682  4682 D SapService: Received stop request...Stopping profile...
11-03 12:29:32.480  4682  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:29:32.480  4682  4682 V SapService: stop()
11-03 12:29:32.480  4682  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 12:29:32.480  4682  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:29:32.480  4682  4768 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 12:29:32.481  4682  4682 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:32.481  4682  4682 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:32.482  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:32.482  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:32.483  4682  4682 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:32.483  4682  4682 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:32.483  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:32.483  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:32.483  4682  4682 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 12:29:32.483  4682  4682 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 12:29:32.483  4682  4682 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:32.484  4682  4682 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:32.484  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:32.484  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:32.484  4682  4682 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-03 12:29:32.485  4682  4682 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-03 12:29:32.485  4682  4682 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:32.485  4682  4682 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:32.485  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:32.485  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:32.485  4682  4682 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 12:29:32.486  4682  4682 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 12:29:32.487  4682  4682 D BluetoothMapService: MAP Service closeService in
11-03 12:29:32.487  4682  4682 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:32.487  4682  4682 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:32.487  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:32.487  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:32.487  4682  4682 D BluetoothMapService: cleanup()
11-03 12:29:32.487  4682  4682 D BluetoothMapService: MAP Service closeService in
11-03 12:29:32.487  4682  4682 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:32.487  4682  4682 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:32.487  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:32.487  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:32.487  4682  4768 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 12:29:32.487  4682  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:29:32.488  4682  4768 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 12:29:32.488  4682  4768 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 12:29:32.488  4682  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:29:32.488  4682  4764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 12:29:32.488  4682  4888 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 12:29:32.488  4682  4888 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 12:29:32.488  4682  4764 D BluetoothAdapterProperties: Setting state to 15
11-03 12:29:32.488  4682  4764 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 12:29:32.488  4682  4888 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 12:29:32.488  4682  4888 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 12:29:32.489   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:29:32.489  4682  4764 I BluetoothAdapterState: Entering BleOnState
11-03 12:29:32.489  3174  4020 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-03 12:29:32.493   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 12:29:32.493  3174  3189 D BluetoothPan: onBluetoothStateChange on: false
11-03 12:29:32.494   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:29:32.494  3174  3187 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 12:29:32.495  3174  4019 D BluetoothMap: onBluetoothStateChange: up=false
11-03 12:29:32.496  3174  4020 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 12:29:32.496  3770  4021 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:29:32.497  3174  3189 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:29:32.497   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:29:32.497  4682  4764 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 12:29:32.497  4682  4764 D BluetoothAdapterProperties: Setting state to 16
11-03 12:29:32.497  4682  4764 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 12:29:32.498  4682  4764 D BluetoothAdapterProperties: onBleDisable
11-03 12:29:32.498  4682  4764 I BluetoothAdapterState: Entering PendingCommandState
11-03 12:29:32.498  4682  4765 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-03 12:29:32.499  4682  4768 D BluetoothAdapterProperties: Scan Mode:20
11-03 12:29:32.500  4682  4888 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 12:29:32.500  4682  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:29:32.501  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:32.503  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:32.504  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:32.505  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:32.507  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:32.510  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:32.514  5756  5756 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-03 12:29:32.526  5756  5756 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 12:29:32.532   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c3195d:true
,11-03 12:29:32.532  3607  3607 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 12:29:32.546   932  3450 I ActivityManager: Start proc 5768:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-03 12:29:32.558  5756  5756 D LocalBluetoothProfileManager: Adding local MAP profile
,11-03 12:29:32.561  5756  5756 D BluetoothMap: Create BluetoothMap proxy object
,11-03 12:29:32.577  5756  5756 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-03 12:29:32.585  5768  5768 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-03 12:29:32.593  5756  5756 D DockEventReceiver: finishStartingService: stopping service
,11-03 12:29:32.609   932  3185 I ActivityManager: Killing 5322:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-03 12:29:32.711  4682  4768 I bt_hci  : shut_down
,11-03 12:29:32.715  4682  4772 D bt_hwcfg: hw_epilog_process
,11-03 12:29:32.715  4682  4772 I bt_vendor: low_power_mode_cb
,11-03 12:29:32.718  4682  4772 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-03 12:29:32.718  4682  4772 I bt_vendor: epilog_cb
11-03 12:29:32.718  4682  4772 I bt_hci  : epilog_finished_callback
11-03 12:29:32.720  4682  4768 I bt_hci_h4: hal_close
11-03 12:29:32.720  4682  4768 I bt_userial_vendor: device fd = 54 close
,11-03 12:29:32.785  5768  5768 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.File.exists(File.java:361)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-03 12:29:32.785  5768  5768 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:29:32.785  5768  5768 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:29:32.785  5768  5768 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.e.b(PG:170)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:29:32.785  5768  5768 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.k.d(PG:583)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.e.b(PG:170)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:29:32.785  5768  5768 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.io.File.exists(File.java:361)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:29:32.785  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:29:32.786  5768  5768 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at java.io.File.exists(File.java:361)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:29:32.786  5768  5768 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:29:32.786  5768  5768 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:29:32.789  5756  5756 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 12:29:32.795  3607  3607 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:29:32.810  5756  5756 D DockEventReceiver: finishStartingService: stopping service
11-03 12:29:32.815   932  3817 I ActivityManager: Killing 3921:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-03 12:29:32.863  4682  4765 D bt_stack_manager: event_shut_down_stack finished.
,11-03 12:29:32.863  4682  4764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 12:29:32.865  4682  4682 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 12:29:32.865  4682  4764 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-03 12:29:32.865  4682  4682 D BtGatt.GattService: Received stop request...Stopping profile...
11-03 12:29:32.865  4682  4682 D BtGatt.GattService: stop()
11-03 12:29:32.866  4682  4682 D BtGatt.AdvertiseManager: advertise clients cleared
11-03 12:29:32.867  4682  4682 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:32.867  4682  4682 V BluetoothAdapterState: isTurningOn()=false
,11-03 12:29:32.867  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:32.867  4682  4682 V BluetoothAdapterState: isBleTurningOff()=true
11-03 12:29:32.867  4682  4764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-03 12:29:32.868  4682  4764 D BluetoothAdapterProperties: Setting state to 10
11-03 12:29:32.868  4682  4764 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 12:29:32.869  4682  4764 I BluetoothAdapterState: Entering OffState
11-03 12:29:32.869   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-03 12:29:32.876  4682  4682 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 12:29:32.876  4682  4682 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 12:29:32.876  4682  4765 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-03 12:29:32.878  4682  4682 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-03 12:29:32.886  4682  4682 I art     : System.exit called, status: 0
,11-03 12:29:32.886  4682  4682 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 12:29:32.929   932  3873 I ActivityManager: Process com.android.bluetooth (pid 4682) has died
,11-03 12:29:32.932  5640  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:32.945   932   949 I ActivityManager: Start proc 5800:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 12:29:33.000  5800  5800 D AdapterServiceConfig: Adding HeadsetService
,11-03 12:29:33.000  5800  5800 D AdapterServiceConfig: Adding A2dpService
11-03 12:29:33.000  5800  5800 D AdapterServiceConfig: Adding HidService
11-03 12:29:33.000  5800  5800 D AdapterServiceConfig: Adding HealthService
11-03 12:29:33.001  5800  5800 D AdapterServiceConfig: Adding PanService
11-03 12:29:33.001  5800  5800 D AdapterServiceConfig: Adding GattService
11-03 12:29:33.001  5800  5800 D AdapterServiceConfig: Adding BluetoothMapService
11-03 12:29:33.001  5800  5800 D AdapterServiceConfig: Adding SapService
,11-03 12:29:33.007   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bf0b1da:true
,11-03 12:29:33.008  5800  5800 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 12:29:33.009  5800  5800 I bt_bluedroid: init
,11-03 12:29:33.010  5800  5812 I BluetoothAdapterState: Entering OffState
,11-03 12:29:33.011  5800  5813 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 12:29:33.011  5800  5813 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 12:29:33.011  5800  5813 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 12:29:33.011  5800  5813 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-03 12:29:33.012  5800  5800 I bt_bluedroid: get_profile_interface socket
,11-03 12:29:33.013  5800  5800 I bt_bluedroid: get_profile_interface sdp
,11-03 12:29:33.013  5800  5816 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 12:29:33.015  5800  5816 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 12:29:33.016  5800  5811 I bt_bluedroid: config_hci_snoop_log
,11-03 12:29:33.017   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
11-03 12:29:33.020  5800  5812 D BluetoothAdapterState: Current state: OFF, message: 0
,11-03 12:29:33.020  5800  5812 D BluetoothAdapterProperties: Setting state to 14
,11-03 12:29:33.020  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-03 12:29:33.022  5800  5812 D BluetoothBondStateMachine: make
,11-03 12:29:33.023  5800  5817 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 12:29:33.025  5800  5812 I BluetoothAdapterState: Entering PendingCommandState
,11-03 12:29:33.026  5800  5800 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 12:29:33.027  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
,11-03 12:29:33.027  5800  5800 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 12:29:33.028  5800  5800 D BtGatt.GattService: Received start request. Starting profile...
11-03 12:29:33.028  5800  5800 D BtGatt.GattService: start()
11-03 12:29:33.028  5800  5800 I bt_bluedroid: get_profile_interface gatt
,11-03 12:29:33.028  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
11-03 12:29:33.028  5800  5800 D BtGatt.AdvertiseManager: advertise manager created
,11-03 12:29:33.031  5800  5800 V BluetoothAdapterState: isTurningOff()=false
,11-03 12:29:33.031  5800  5800 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:33.031  5800  5800 V BluetoothAdapterState: isBleTurningOn()=true
11-03 12:29:33.031  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 12:29:33.032  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-03 12:29:33.033  5800  5812 I bt_bluedroid: bt_bluedroid
11-03 12:29:33.033  5800  5813 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-03 12:29:33.033  5800  5813 I bt_hci  : start_up
,11-03 12:29:33.038  5800  5813 I bt_vendor: alloc value 0xf4111871
,11-03 12:29:33.038  5800  5813 I bt_vendor: init
11-03 12:29:33.038  5800  5813 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 12:29:33.038  5800  5813 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 12:29:33.049  5768  5792 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-03 12:29:33.057   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9e37b83:true
,11-03 12:29:33.146  5823  5823 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 12:29:33.147  5800  5813 D bt_hci  : start_up starting async portion
11-03 12:29:33.148  5800  5820 I bt_hci  : event_finish_startup
11-03 12:29:33.148  5800  5820 I bt_hci_h4: hal_open
11-03 12:29:33.148  5800  5820 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-03 12:29:33.149  5800  5820 I bt_userial_vendor: device fd = 54 open
,11-03 12:29:33.162  5800  5820 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 12:29:33.164  5800  5820 D bt_hwcfg: Chipset BCM4358A3
,11-03 12:29:33.164  5800  5820 D bt_hwcfg: Target name = [BCM4358A3]
11-03 12:29:33.164  5800  5820 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 12:29:33.441  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-03 12:29:33.536  5800  5820 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 12:29:33.537  5800  5820 D bt_hwcfg: Settlement delay -- 100 ms
11-03 12:29:33.537  5800  5820 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 12:29:33.659  5800  5820 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 12:29:33.660  5800  5820 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-03 12:29:33.661  5800  5820 I bt_hwcfg: vendor lib fwcfg completed
,11-03 12:29:33.661  5800  5820 I bt_vendor: firmware callback
11-03 12:29:33.661  5800  5820 I bt_hci  : firmware_config_callback
,11-03 12:29:33.669  5800  5825 I bt_btu  : btu_task pending for preload complete event
11-03 12:29:33.670  5800  5825 I bt_btu_task: Bluetooth chip preload is complete
11-03 12:29:33.670  5800  5825 I bt_btu  : btu_task received preload complete event
,11-03 12:29:33.675  5800  5825 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 12:29:33.675  5800  5825 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 12:29:33.676  5800  5825 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 12:29:33.676  5800  5825 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 12:29:33.676  5800  5825 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-03 12:29:33.676  5800  5825 I         : BTE_InitTraceLevels -- TRC_A2D
11-03 12:29:33.676  5800  5825 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-03 12:29:33.676  5800  5825 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 12:29:33.676  5800  5825 I         : BTE_InitTraceLevels -- TRC_GAP
11-03 12:29:33.676  5800  5825 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 12:29:33.676  5800  5825 I         : BTE_InitTraceLevels -- TRC_SDP
,11-03 12:29:33.677  5800  5825 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 12:29:33.677  5800  5825 I         : BTE_InitTraceLevels -- TRC_SMP
,11-03 12:29:33.677  5800  5825 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-03 12:29:33.677  5800  5825 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 12:29:33.759  5800  5825 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf408f549
11-03 12:29:33.759  5800  5825 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf408f549 
,11-03 12:29:33.769  5800  5816 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 12:29:33.771  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 12:29:33.771  5800  5816 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-03 12:29:33.774  5800  5816 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 12:29:33.776  5800  5816 D BluetoothAdapterProperties: Scan Mode:20
11-03 12:29:33.777  5800  5816 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 12:29:33.777  5800  5816 D bt_hci  : do_postload posting postload work item
11-03 12:29:33.778  5800  5820 I bt_hci  : event_postload
11-03 12:29:33.778  5800  5820 I bt_vendor: sco_config_cb
11-03 12:29:33.778  5800  5820 I bt_hci  : sco_config_callback postload finished.
11-03 12:29:33.780  5800  5816 D bt_bte_conf: Device ID record 1 : primary
11-03 12:29:33.781  5800  5816 D bt_bte_conf:   vendorId            = 000f
11-03 12:29:33.781  5800  5816 D bt_bte_conf:   vendorIdSource      = 0001
,11-03 12:29:33.781  5800  5816 D bt_bte_conf:   product             = 1200
11-03 12:29:33.781  5800  5816 D bt_bte_conf:   version             = 1436
11-03 12:29:33.781  5800  5816 D bt_bte_conf:   clientExecutableURL = 
,11-03 12:29:33.781  5800  5816 D bt_bte_conf:   serviceDescription  = 
,11-03 12:29:33.781  5800  5816 D bt_bte_conf:   documentationURL    = 
11-03 12:29:33.781  5800  5816 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 12:29:33.782  5800  5813 D bt_stack_manager: event_start_up_stack finished
11-03 12:29:33.782  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-03 12:29:33.783  5800  5812 D BluetoothAdapterProperties: Setting state to 15
11-03 12:29:33.783  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-03 12:29:33.785  5800  5812 I BluetoothAdapterState: Entering BleOnState
11-03 12:29:33.788  5800  5820 I bt_vendor: low_power_mode_cb
11-03 12:29:33.789  5800  5812 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 12:29:33.790  5800  5812 D BluetoothAdapterProperties: Setting state to 11
11-03 12:29:33.790  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:33.790  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-03 12:29:33.793  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:33.795  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
,11-03 12:29:33.799  5800  5800 D HeadsetService: Received start request. Starting profile...
11-03 12:29:33.801  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:33.803  5800  5800 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 12:29:33.803  5800  5800 D HeadsetStateMachine: make
,11-03 12:29:33.805  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:33.807  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:33.809  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:33.812  5800  5812 I BluetoothAdapterState: Entering PendingCommandState
,11-03 12:29:33.816  5800  5800 D HeadsetStateMachine: max_hf_connections = 1
11-03 12:29:33.816  5800  5800 I bt_bluedroid: get_profile_interface handsfree
11-03 12:29:33.817  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 12:29:33.817  5800  5816 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-03 12:29:33.819  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
,11-03 12:29:33.820  5800  5800 D A2dpService: Received start request. Starting profile...
,11-03 12:29:33.821  5800  5800 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 12:29:33.821  5800  5800 I bt_bluedroid: get_profile_interface avrcp
,11-03 12:29:33.826  5800  5800 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-03 12:29:33.827  5800  5800 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 12:29:33.827  5800  5800 D A2dpStateMachine: make
,11-03 12:29:33.831  5800  5800 I bt_bluedroid: get_profile_interface a2dp
,11-03 12:29:33.831  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 12:29:33.832  5800  5833 D A2dpStateMachine: Enter Disconnected: -2
,11-03 12:29:33.833  5800  5800 I BluetoothHidServiceJni: classInitNative: succeeds
,11-03 12:29:33.834  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
11-03 12:29:33.835  5756  5756 D BluetoothInputDevice: Proxy object connected
,11-03 12:29:33.835  5800  5800 D HidService: Received start request. Starting profile...
,11-03 12:29:33.835  5800  5800 I bt_bluedroid: get_profile_interface hidhost
11-03 12:29:33.835  5800  5800 D HidService: setHidService(): set to: null
11-03 12:29:33.835  5800  5816 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf407056d
11-03 12:29:33.836  5756  5756 D HidProfile: Bluetooth service connected
11-03 12:29:33.836  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 12:29:33.836  5800  5800 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-03 12:29:33.837  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
11-03 12:29:33.837  5800  5800 D HealthService: Received start request. Starting profile...
,11-03 12:29:33.839  5800  5800 I bt_bluedroid: get_profile_interface health
,11-03 12:29:33.839  5800  5800 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-03 12:29:33.840  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
,11-03 12:29:33.841  5756  5756 D BluetoothPan: BluetoothPAN Proxy object connected
,11-03 12:29:33.842  5756  5756 D PanProfile: Bluetooth service connected
11-03 12:29:33.842  5800  5800 D PanService: Received start request. Starting profile...
11-03 12:29:33.842  5800  5800 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 12:29:33.843  5800  5800 I bt_bluedroid: get_profile_interface pan
11-03 12:29:33.843  5800  5816 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-03 12:29:33.846  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
11-03 12:29:33.846  3607  3607 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:29:33.848  5800  5800 D BluetoothMapService: Received start request. Starting profile...
11-03 12:29:33.848  5800  5800 D BluetoothMapService: start()
11-03 12:29:33.850  5800  5800 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-03 12:29:33.851  5800  5800 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 12:29:33.851  5800  5800 D BluetoothMapAppObserver: createReceiver()
11-03 12:29:33.852  5800  5800 D BluetoothMapAppObserver: initObservers()
11-03 12:29:33.852  5800  5800 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 12:29:33.860  5800  5800 V SapService: SapBinder()
,11-03 12:29:33.860  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
11-03 12:29:33.861  5800  5800 D SapService: Received start request. Starting profile...
11-03 12:29:33.861  5800  5800 V SapService: start()
,11-03 12:29:33.863  5800  5800 V BluetoothAdapterState: isTurningOff()=false
,11-03 12:29:33.863  5800  5800 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:33.863  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:33.863  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isTurningOff()=false
,11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isTurningOn()=true
,11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.864  5800  5831 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:33.864  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.865  5800  5800 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:33.865  5800  5800 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:33.865  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:33.865  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.860  5756  5756 D BluetoothMap: Proxy object connected
,11-03 12:29:33.866  5800  5800 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:33.866  5800  5800 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:33.866  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:33.866  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.867  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 12:29:33.867  5800  5812 D BluetoothAdapterProperties: ScanMode =  20
11-03 12:29:33.867  5800  5812 D BluetoothAdapterProperties: State =  11
11-03 12:29:33.868  5756  5756 D MapProfile: Bluetooth service connected
11-03 12:29:33.869  5756  5756 D BluetoothMap: getConnectedDevices()
11-03 12:29:33.869  5800  5816 D BluetoothAdapterProperties: Scan Mode:21
11-03 12:29:33.869  5800  5816 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 12:29:33.869  5800  5812 D BluetoothAdapterProperties: Setting state to 12
,11-03 12:29:33.869  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 12:29:33.869  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 12:29:33.869   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:29:33.869  5800  5812 I BluetoothAdapterState: Entering OnState
11-03 12:29:33.869  5756  5756 D BluetoothMap: Bluetooth is Not enabled
11-03 12:29:33.870  3174  4019 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 12:29:33.871   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 12:29:33.871  3174  3174 D BluetoothInputDevice: Proxy object connected
11-03 12:29:33.871  3174  3174 D HidProfile: Bluetooth service connected
11-03 12:29:33.872  5640  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-03 12:29:33.872  5756  5767 D BluetoothPan: onBluetoothStateChange on: true
,11-03 12:29:33.873  3174  3187 D BluetoothPan: onBluetoothStateChange on: true
,11-03 12:29:33.873   932   932 D BluetoothA2dp: Proxy object connected
11-03 12:29:33.875  5640  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-03 12:29:33.876   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:29:33.877  3174  3174 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 12:29:33.877  3174  3174 D PanProfile: Bluetooth service connected
11-03 12:29:33.877  3174  4019 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 12:29:33.878  3174  3189 D BluetoothMap: onBluetoothStateChange: up=true
11-03 12:29:33.879  5800  5800 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 12:29:33.879  5800  5800 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-03 12:29:33.880  3174  3174 D BluetoothA2dp: Proxy object connected
11-03 12:29:33.881  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:33.881  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:33.881  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:33.881  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:33.881  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:33.881  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:33.881  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:33.881  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:33.882  3174  4020 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 12:29:33.883  3174  3174 D BluetoothMap: Proxy object connected
11-03 12:29:33.883  3174  3174 D MapProfile: Bluetooth service connected
11-03 12:29:33.883  3174  3174 D BluetoothMap: getConnectedDevices()
11-03 12:29:33.884  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:33.884  5800  5800 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:29:33.884  3770  3798 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:29:33.885  5756  5766 D BluetoothMap: onBluetoothStateChange: up=true
11-03 12:29:33.886  5756  5767 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 12:29:33.886  5756  5766 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 12:29:33.887  5800  5800 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:29:33.888  3174  3187 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:29:33.888  5800  5800 D ObexServerSockets: Succeed to create listening sockets 
,11-03 12:29:33.888  5800  5800 D ObexServerSockets0: startAccept()
11-03 12:29:33.888  5800  5800 D ObexServerSockets0: prepareForNewConnect()
11-03 12:29:33.888   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:29:33.888  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:33.888  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:33.888  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:33.888  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:33.888  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:33.888  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:33.888  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:33.888  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:33.890  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:33.891  5800  5800 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 12:29:33.891  5800  5800 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 12:29:33.892  5800  5800 D BluetoothMapService: onReceive
11-03 12:29:33.892  5800  5800 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 12:29:33.892  5800  5800 D BluetoothMapService: STATE_ON
11-03 12:29:33.892   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 12:29:33.892  5800  5839 D ObexServerSockets0: Accepting socket connection...
11-03 12:29:33.894  5800  5840 D ObexServerSockets0: Accepting socket connection...
11-03 12:29:33.896  5756  5756 D LocalBluetoothProfileManager: Adding local A2DP profile
11-03 12:29:33.897  5800  5842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:29:33.898  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:33.898  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:33.898  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:33.898  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:33.898  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:33.898  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:33.898  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:33.898  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:33.900  5800  5842 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 12:29:33.901  5800  5842 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-03 12:29:33.901  5756  5756 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-03 12:29:33.901  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:33.901  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-03 12:29:33.903  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:33.905  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:33.906  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:33.909  5756  5756 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 12:29:33.910  5756  5756 D BluetoothA2dp: Proxy object connected
,11-03 12:29:33.913  5800  5800 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 12:29:33.913  5800  5800 D ObexServerSockets0: prepareForNewConnect()
11-03 12:29:33.914  3607  3607 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:29:33.915  5756  5756 D DockEventReceiver: finishStartingService: stopping service
,11-03 12:29:33.921  3174  3174 D BluetoothPbap: Proxy object connected
,11-03 12:29:33.921  3174  3174 D PbapServerProfile: Bluetooth service connected
,11-03 12:29:33.921  5756  5756 D BluetoothPbap: Proxy object connected
,11-03 12:29:33.922  5756  5756 D PbapServerProfile: Bluetooth service connected
,11-03 12:29:33.929  5800  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:29:33.942  5640  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:33.943  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-03 12:29:33.943  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 12:29:33.945  5640  5687 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-03 12:29:33.945  5800  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:29:33.945  5640  5687 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
11-03 12:29:33.946  5800  5850 I BtOppRfcommListener: Accept thread started.
11-03 12:29:33.947  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:33.949  5800  5812 D BluetoothAdapterState: Current state: ON, message: 23
,11-03 12:29:33.949  5800  5812 D BluetoothAdapterProperties: Setting state to 13
,11-03 12:29:33.949  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-03 12:29:33.950  5800  5812 D BluetoothAdapterProperties: onBluetoothDisable()
11-03 12:29:33.951  5800  5812 I BluetoothAdapterState: Entering PendingCommandState
11-03 12:29:33.952  5800  5800 D BluetoothMapService: onReceive
11-03 12:29:33.952  5800  5800 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 12:29:33.952  5800  5800 D BluetoothMapService: STATE_TURNING_OFF
11-03 12:29:33.952  5800  5800 D BluetoothMapService: MAP Service closeService in
,11-03 12:29:33.952  5800  5800 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 12:29:33.952  5800  5800 D ObexServerSockets0: shutdown(block = true)
11-03 12:29:33.953  5800  5800 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 12:29:33.953  5800  5839 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-03 12:29:33.953  5800  5800 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 12:29:33.953  5800  5840 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 12:29:33.954  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:29:33.954  5800  5827 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 12:29:33.954  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:33.954  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:33.954  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:33.954  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:33.954  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:29:33.954  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:33.954  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:33.954  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:33.954  5756  5756 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 12:29:33.954  5800  5800 I BtOppRfcommListener: stopping Accept Thread
11-03 12:29:33.955  5800  5850 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 12:29:33.955  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:29:33.955  5800  5850 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-03 12:29:33.955  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:33.958  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:29:33.958  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:33.958  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:33.958  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:33.958  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:33.958  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:29:33.958  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:33.958  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:33.958  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:33.958  5800  5816 D BluetoothAdapterProperties: Scan Mode:20
11-03 12:29:33.958  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-03 12:29:33.959  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:29:33.959  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:33.961  5800  5800 D HeadsetService: Received stop request...Stopping profile...
,11-03 12:29:33.961  3607  3607 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:29:33.962  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:33.963  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:33.966  5800  5800 D A2dpService: Received stop request...Stopping profile...
11-03 12:29:33.966  3174  3174 D BluetoothPbap: Proxy object disconnected
11-03 12:29:33.966  5800  5833 D A2dpStateMachine: Exit Disconnected: -1
11-03 12:29:33.966  3174  3174 D PbapServerProfile: Bluetooth service disconnected
11-03 12:29:33.967   932   932 D BluetoothA2dp: Proxy object disconnected
,11-03 12:29:33.970  5800  5800 D HidService: Received stop request...Stopping profile...
,11-03 12:29:33.970  5800  5800 D HidService: Stopping Bluetooth HidService
11-03 12:29:33.970  3174  3174 D BluetoothA2dp: Proxy object disconnected
11-03 12:29:33.971  5756  5756 D DockEventReceiver: finishStartingService: stopping service
11-03 12:29:33.972  3174  3174 D BluetoothInputDevice: Proxy object disconnected
11-03 12:29:33.972  3174  3174 D HidProfile: Bluetooth service disconnected
11-03 12:29:33.972  5800  5800 V BluetoothAdapterState: isTurningOff()=true
,11-03 12:29:33.972  5800  5800 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:33.972  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:33.972  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.972  5756  5756 D BluetoothPbap: Proxy object disconnected
11-03 12:29:33.972  5756  5756 D PbapServerProfile: Bluetooth service disconnected
,11-03 12:29:33.973  5756  5756 D BluetoothA2dp: Proxy object disconnected
11-03 12:29:33.975  5800  5800 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 12:29:33.975  5756  5756 D BluetoothInputDevice: Proxy object disconnected
11-03 12:29:33.975  5756  5756 D HidProfile: Bluetooth service disconnected
11-03 12:29:33.975  5800  5800 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 12:29:33.975  5800  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:29:33.975  5800  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:29:33.975  5800  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:29:33.975  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 12:29:33.975  5800  5816 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
11-03 12:29:33.976  5800  5800 D HealthService: Received stop request...Stopping profile...
,11-03 12:29:33.977  5800  5800 D PanService: Received stop request...Stopping profile...
11-03 12:29:33.978  3174  3174 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 12:29:33.978  3174  3174 D PanProfile: Bluetooth service disconnected
11-03 12:29:33.979  5756  5756 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 12:29:33.979  5756  5756 D PanProfile: Bluetooth service disconnected
,11-03 12:29:33.979  5800  5800 D BluetoothMapService: Received stop request...Stopping profile...
11-03 12:29:33.979  5800  5800 D BluetoothMapService: stop()
11-03 12:29:33.979  5800  5800 D BluetoothMapAppObserver: deinitObservers()
11-03 12:29:33.979  5800  5800 D BluetoothMapAppObserver: removeReceiver()
11-03 12:29:33.981  5756  5756 D BluetoothMap: Proxy object disconnected
11-03 12:29:33.981  3174  3174 D BluetoothMap: Proxy object disconnected
,11-03 12:29:33.981  5756  5756 D MapProfile: Bluetooth service disconnected
11-03 12:29:33.981  3174  3174 D MapProfile: Bluetooth service disconnected
11-03 12:29:33.982  5800  5800 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:33.982  5800  5800 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:33.982  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:33.982  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.983  5800  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 12:29:33.983  5800  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 12:29:33.983  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 12:29:33.983  5800  5825 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 12:29:33.983  5800  5825 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 12:29:33.983  5800  5825 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 12:29:33.983  5800  5825 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 12:29:33.983  5800  5800 D SapService: Received stop request...Stopping profile...
11-03 12:29:33.983  5800  5800 V SapService: stop()
11-03 12:29:33.985  5800  5800 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:33.985  5800  5800 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:33.985  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 12:29:33.985  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.985  5800  5800 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 12:29:33.985  5800  5800 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 12:29:33.986  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 12:29:33.987  5800  5800 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:33.987  5800  5800 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:33.987  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:33.987  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.987  5800  5800 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-03 12:29:33.987  5800  5816 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-03 12:29:33.987  5800  5800 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-03 12:29:33.988  5800  5800 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:33.988  5800  5800 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:33.988  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:33.988  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.988  5800  5800 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 12:29:33.988  5800  5800 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 12:29:33.988  5800  5800 D BluetoothMapService: MAP Service closeService in
11-03 12:29:33.989  5800  5800 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:33.989  5800  5800 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:33.989  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 12:29:33.989  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.989  5800  5800 D BluetoothMapService: cleanup()
11-03 12:29:33.989  5800  5800 D BluetoothMapService: MAP Service closeService in
11-03 12:29:33.989  5800  5800 V BluetoothAdapterState: isTurningOff()=true
11-03 12:29:33.989  5800  5800 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:33.989  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:33.989  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:33.989  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 12:29:33.989  5800  5812 D BluetoothAdapterProperties: Setting state to 15
11-03 12:29:33.989  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-03 12:29:33.990  5756  5766 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 12:29:33.990  5800  5812 I BluetoothAdapterState: Entering BleOnState
11-03 12:29:33.991   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:29:33.991  3174  4019 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-03 12:29:33.991   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 12:29:33.992  5756  5767 D BluetoothPan: onBluetoothStateChange on: false
11-03 12:29:33.992  3174  3187 D BluetoothPan: onBluetoothStateChange on: false
,11-03 12:29:33.992   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-03 12:29:33.993  3174  3189 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 12:29:33.993  5756  5766 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:29:33.993  3174  4020 D BluetoothMap: onBluetoothStateChange: up=false
11-03 12:29:33.994  3174  4019 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 12:29:33.994  3770  3810 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:29:33.995  5756  5767 D BluetoothMap: onBluetoothStateChange: up=false
11-03 12:29:33.995  5756  5766 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 12:29:33.996  5756  5767 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 12:29:33.996  3174  3187 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:29:33.996   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:29:33.997  5800  5812 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 12:29:33.997  5800  5812 D BluetoothAdapterProperties: Setting state to 16
11-03 12:29:33.997  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 12:29:33.999  5800  5812 D BluetoothAdapterProperties: onBleDisable
11-03 12:29:33.999  5800  5812 I BluetoothAdapterState: Entering PendingCommandState
,11-03 12:29:33.999  5800  5813 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-03 12:29:34.001  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:34.001  5756  5756 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 12:29:34.001  5800  5825 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 12:29:34.002  5800  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 12:29:34.003  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:34.004  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:34.006  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:34.006  5800  5816 D BluetoothAdapterProperties: Scan Mode:20
11-03 12:29:34.007  3607  3607 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:29:34.008  5756  5756 D DockEventReceiver: finishStartingService: stopping service
,11-03 12:29:34.202  5800  5816 I bt_hci  : shut_down
11-03 12:29:34.202  5800  5820 D bt_hwcfg: hw_epilog_process
,11-03 12:29:34.203  5800  5820 I bt_vendor: low_power_mode_cb
,11-03 12:29:34.205  5800  5820 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-03 12:29:34.206  5800  5820 I bt_vendor: epilog_cb
11-03 12:29:34.206  5800  5820 I bt_hci  : epilog_finished_callback
11-03 12:29:34.206  5800  5816 I bt_hci_h4: hal_close
11-03 12:29:34.207  5800  5816 I bt_userial_vendor: device fd = 54 close
,11-03 12:29:34.334  5800  5813 D bt_stack_manager: event_shut_down_stack finished.
,11-03 12:29:34.335  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 12:29:34.339  5800  5812 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-03 12:29:34.339  5800  5800 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 12:29:34.340  5800  5800 D BtGatt.GattService: Received stop request...Stopping profile...
11-03 12:29:34.340  5800  5800 D BtGatt.GattService: stop()
11-03 12:29:34.340  5800  5800 D BtGatt.AdvertiseManager: advertise clients cleared
,11-03 12:29:34.344  5800  5800 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:34.344  5800  5800 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:34.344  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 12:29:34.344  5800  5800 V BluetoothAdapterState: isBleTurningOff()=true
11-03 12:29:34.345  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-03 12:29:34.346  5800  5812 D BluetoothAdapterProperties: Setting state to 10
11-03 12:29:34.346  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-03 12:29:34.347  5800  5812 I BluetoothAdapterState: Entering OffState
,11-03 12:29:34.349   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-03 12:29:34.363  5800  5800 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 12:29:34.363  5800  5800 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 12:29:34.364  5800  5800 I BluetoothServiceJni: cleanupNative: return from cleanup
11-03 12:29:34.366  5800  5813 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 12:29:34.374  5800  5800 I art     : System.exit called, status: 0
11-03 12:29:34.374  5800  5800 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 12:29:34.405   932   942 I ActivityManager: Process com.android.bluetooth (pid 5800) has died
,11-03 12:29:34.449  5640  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:29:34.449  5640  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:34.449  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:34.449  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:34.449  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:34.449  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:29:34.449  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:34.449  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:34.449  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:34.450  5640  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 12:29:34.450  5640  5711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:34.453  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:34.479   932   949 I ActivityManager: Start proc 5855:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 12:29:34.544  5855  5855 D AdapterServiceConfig: Adding HeadsetService
,11-03 12:29:34.545  5855  5855 D AdapterServiceConfig: Adding A2dpService
11-03 12:29:34.545  5855  5855 D AdapterServiceConfig: Adding HidService
11-03 12:29:34.545  5855  5855 D AdapterServiceConfig: Adding HealthService
11-03 12:29:34.545  5855  5855 D AdapterServiceConfig: Adding PanService
11-03 12:29:34.545  5855  5855 D AdapterServiceConfig: Adding GattService
11-03 12:29:34.545  5855  5855 D AdapterServiceConfig: Adding BluetoothMapService
,11-03 12:29:34.545  5855  5855 D AdapterServiceConfig: Adding SapService
,11-03 12:29:34.557   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c1e343:true
,11-03 12:29:34.558  5855  5855 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 12:29:34.560  5855  5855 I bt_bluedroid: init
,11-03 12:29:34.560  5855  5867 I BluetoothAdapterState: Entering OffState
,11-03 12:29:34.562  5855  5868 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 12:29:34.562  5855  5868 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 12:29:34.562  5855  5868 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 12:29:34.562  5855  5868 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-03 12:29:34.563  5855  5855 I bt_bluedroid: get_profile_interface socket
,11-03 12:29:34.564  5855  5871 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 12:29:34.565  5855  5855 I bt_bluedroid: get_profile_interface sdp
,11-03 12:29:34.566  5855  5871 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 12:29:34.569  5855  5866 I bt_bluedroid: config_hci_snoop_log
,11-03 12:29:34.570   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-03 12:29:34.574  5855  5867 D BluetoothAdapterState: Current state: OFF, message: 0
11-03 12:29:34.574  5855  5867 D BluetoothAdapterProperties: Setting state to 14
,11-03 12:29:34.574  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-03 12:29:34.576  5855  5867 D BluetoothBondStateMachine: make
,11-03 12:29:34.578  5855  5873 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 12:29:34.580  5855  5867 I BluetoothAdapterState: Entering PendingCommandState
,11-03 12:29:34.581  5855  5855 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 12:29:34.583  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
11-03 12:29:34.584  5855  5855 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 12:29:34.584  5855  5855 D BtGatt.GattService: Received start request. Starting profile...
11-03 12:29:34.584  5855  5855 D BtGatt.GattService: start()
11-03 12:29:34.584  5855  5855 I bt_bluedroid: get_profile_interface gatt
,11-03 12:29:34.585  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
11-03 12:29:34.585  5855  5855 D BtGatt.AdvertiseManager: advertise manager created
,11-03 12:29:34.590  5855  5855 V BluetoothAdapterState: isTurningOff()=false
,11-03 12:29:34.590  5855  5855 V BluetoothAdapterState: isTurningOn()=false
11-03 12:29:34.590  5855  5855 V BluetoothAdapterState: isBleTurningOn()=true
11-03 12:29:34.590  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:34.590  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-03 12:29:34.591  5855  5867 I bt_bluedroid: bt_bluedroid
11-03 12:29:34.592  5855  5868 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-03 12:29:34.592  5855  5868 I bt_hci  : start_up
,11-03 12:29:34.597  5855  5868 I bt_vendor: alloc value 0xf4111871
,11-03 12:29:34.597  5855  5868 I bt_vendor: init
11-03 12:29:34.597  5855  5868 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 12:29:34.597  5855  5868 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 12:29:34.707  5855  5868 D bt_hci  : start_up starting async portion
,11-03 12:29:34.708  5855  5876 I bt_hci  : event_finish_startup
11-03 12:29:34.708  5855  5876 I bt_hci_h4: hal_open
11-03 12:29:34.708  5855  5876 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 12:29:34.706  5877  5877 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 12:29:34.712  5855  5876 I bt_userial_vendor: device fd = 54 open
,11-03 12:29:34.726  5855  5876 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 12:29:34.729  5855  5876 D bt_hwcfg: Chipset BCM4358A3
,11-03 12:29:34.729  5855  5876 D bt_hwcfg: Target name = [BCM4358A3]
11-03 12:29:34.730  5855  5876 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 12:29:34.960  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-03 12:29:35.126  5855  5876 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 12:29:35.126  5855  5876 D bt_hwcfg: Settlement delay -- 100 ms
,11-03 12:29:35.126  5855  5876 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 12:29:35.249  5855  5876 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-03 12:29:35.250  5855  5876 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-03 12:29:35.251  5855  5876 I bt_hwcfg: vendor lib fwcfg completed
,11-03 12:29:35.251  5855  5876 I bt_vendor: firmware callback
11-03 12:29:35.251  5855  5876 I bt_hci  : firmware_config_callback
,11-03 12:29:35.261  5855  5879 I bt_btu  : btu_task pending for preload complete event
,11-03 12:29:35.261  5855  5879 I bt_btu_task: Bluetooth chip preload is complete
,11-03 12:29:35.261  5855  5879 I bt_btu  : btu_task received preload complete event
,11-03 12:29:35.268  5855  5879 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 12:29:35.268  5855  5879 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 12:29:35.268  5855  5879 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 12:29:35.268  5855  5879 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-03 12:29:35.269  5855  5879 I         : BTE_InitTraceLevels -- TRC_AVRC
11-03 12:29:35.269  5855  5879 I         : BTE_InitTraceLevels -- TRC_A2D
11-03 12:29:35.269  5855  5879 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-03 12:29:35.269  5855  5879 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 12:29:35.269  5855  5879 I         : BTE_InitTraceLevels -- TRC_GAP
11-03 12:29:35.269  5855  5879 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 12:29:35.269  5855  5879 I         : BTE_InitTraceLevels -- TRC_SDP
,11-03 12:29:35.270  5855  5879 I         : BTE_InitTraceLevels -- TRC_GATT
,11-03 12:29:35.270  5855  5879 I         : BTE_InitTraceLevels -- TRC_SMP
,11-03 12:29:35.270  5855  5879 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-03 12:29:35.270  5855  5879 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 12:29:35.353  5855  5879 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf408f549
11-03 12:29:35.353  5855  5879 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf408f549 
,11-03 12:29:35.373  5855  5871 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = true
,11-03 12:29:35.375  5855  5871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 12:29:35.375  5855  5871 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-03 12:29:35.377  5855  5871 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 12:29:35.380  5855  5871 D BluetoothAdapterProperties: Scan Mode:20
11-03 12:29:35.381  5855  5871 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 12:29:35.381  5855  5871 D bt_hci  : do_postload posting postload work item
,11-03 12:29:35.381  5855  5876 I bt_hci  : event_postload
11-03 12:29:35.381  5855  5876 I bt_vendor: sco_config_cb
11-03 12:29:35.381  5855  5876 I bt_hci  : sco_config_callback postload finished.
,11-03 12:29:35.385  5855  5871 D bt_bte_conf: Device ID record 1 : primary
,11-03 12:29:35.386  5855  5871 D bt_bte_conf:   vendorId            = 000f
11-03 12:29:35.386  5855  5871 D bt_bte_conf:   vendorIdSource      = 0001
11-03 12:29:35.386  5855  5871 D bt_bte_conf:   product             = 1200
,11-03 12:29:35.386  5855  5871 D bt_bte_conf:   version             = 1436
11-03 12:29:35.386  5855  5871 D bt_bte_conf:   clientExecutableURL = 
11-03 12:29:35.386  5855  5871 D bt_bte_conf:   serviceDescription  = 
11-03 12:29:35.386  5855  5871 D bt_bte_conf:   documentationURL    = 
11-03 12:29:35.386  5855  5871 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 12:29:35.386  5855  5868 D bt_stack_manager: event_start_up_stack finished
,11-03 12:29:35.387  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-03 12:29:35.388  5855  5867 D BluetoothAdapterProperties: Setting state to 15
11-03 12:29:35.388  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 12:29:35.390  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:35.393  5855  5867 I BluetoothAdapterState: Entering BleOnState
11-03 12:29:35.393  5855  5876 I bt_vendor: low_power_mode_cb
11-03 12:29:35.393  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:35.393  5855  5867 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 12:29:35.394  5855  5867 D BluetoothAdapterProperties: Setting state to 11
11-03 12:29:35.394  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 12:29:35.400  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
,11-03 12:29:35.405  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:35.407  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:35.412  3770  3810 D BluetoothHeadset: Proxy object connected
,11-03 12:29:35.412  5855  5855 D HeadsetService: Received start request. Starting profile...
11-03 12:29:35.412   932   932 D BluetoothHeadset: Proxy object connected
11-03 12:29:35.413  3174  3189 D BluetoothHeadset: Proxy object connected
11-03 12:29:35.413   932   932 D BluetoothHeadset: Proxy object connected
11-03 12:29:35.413   932   932 D BluetoothHeadset: Proxy object connected
11-03 12:29:35.414  5756  5766 D BluetoothHeadset: Proxy object connected
11-03 12:29:35.415  5855  5855 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 12:29:35.415  5855  5855 D HeadsetStateMachine: make
11-03 12:29:35.416  5756  5756 D HeadsetProfile: Bluetooth service connected
11-03 12:29:35.420  3174  3174 D HeadsetProfile: Bluetooth service connected
,11-03 12:29:35.423  5855  5867 I BluetoothAdapterState: Entering PendingCommandState
,11-03 12:29:35.427  5855  5855 D HeadsetStateMachine: max_hf_connections = 1
,11-03 12:29:35.427  5855  5855 I bt_bluedroid: get_profile_interface handsfree
11-03 12:29:35.427  5855  5871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 12:29:35.427  5855  5871 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-03 12:29:35.430  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
11-03 12:29:35.431  5855  5855 D A2dpService: Received start request. Starting profile...
,11-03 12:29:35.431  5855  5855 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-03 12:29:35.432  5855  5855 I bt_bluedroid: get_profile_interface avrcp
,11-03 12:29:35.438  5855  5855 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-03 12:29:35.438  5855  5855 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 12:29:35.438  5855  5855 D A2dpStateMachine: make
11-03 12:29:35.439  5855  5855 I bt_bluedroid: get_profile_interface a2dp
,11-03 12:29:35.439  5855  5871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 12:29:35.442  5855  5855 I BluetoothHidServiceJni: classInitNative: succeeds
11-03 12:29:35.443  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
11-03 12:29:35.443  5855  5886 D A2dpStateMachine: Enter Disconnected: -2
11-03 12:29:35.443  5752  5752 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 12:29:35.444  5855  5855 D HidService: Received start request. Starting profile...
11-03 12:29:35.445  5855  5855 I bt_bluedroid: get_profile_interface hidhost
11-03 12:29:35.445  5855  5855 D HidService: setHidService(): set to: null
,11-03 12:29:35.445  5855  5871 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf407056d
11-03 12:29:35.445  5855  5871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 12:29:35.445  5855  5855 I BluetoothHealthServiceJni: classInitNative: succeeds
11-03 12:29:35.446  3607  3607 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:29:35.446  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
11-03 12:29:35.447  5855  5855 D HealthService: Received start request. Starting profile...
,11-03 12:29:35.448  5855  5855 I bt_bluedroid: get_profile_interface health
,11-03 12:29:35.449  5855  5855 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-03 12:29:35.449  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
,11-03 12:29:35.450  5855  5855 D PanService: Received start request. Starting profile...
,11-03 12:29:35.450  5855  5855 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 12:29:35.450  5855  5855 I bt_bluedroid: get_profile_interface pan
11-03 12:29:35.451  5855  5871 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-03 12:29:35.453  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
11-03 12:29:35.453  5855  5855 D BluetoothMapService: Received start request. Starting profile...
11-03 12:29:35.453  5855  5855 D BluetoothMapService: start()
11-03 12:29:35.455  5752  5752 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 12:29:35.457  5855  5855 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-03 12:29:35.458  5855  5855 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 12:29:35.458  5855  5855 D BluetoothMapAppObserver: createReceiver()
11-03 12:29:35.459  5855  5855 D BluetoothMapAppObserver: initObservers()
11-03 12:29:35.459  5855  5855 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 12:29:35.462  5752  5752 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 12:29:35.465  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-03 12:29:35.466  5752  5752 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-03 12:29:35.466  5855  5855 V SapService: SapBinder()
11-03 12:29:35.466  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
,11-03 12:29:35.467  5855  5855 D SapService: Received start request. Starting profile...
11-03 12:29:35.467  5855  5855 V SapService: start()
,11-03 12:29:35.470  5855  5855 V BluetoothAdapterState: isTurningOff()=false
,11-03 12:29:35.471  5855  5855 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:35.471  5855  5884 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 12:29:35.471  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:35.471  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:35.471  5855  5855 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:35.471  5855  5855 V BluetoothAdapterState: isTurningOn()=true
,11-03 12:29:35.471  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:35.471  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:35.471  5855  5855 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:35.471  5855  5855 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:35.472  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:35.472  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:35.472  5855  5855 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:35.472  5855  5855 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:35.472  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:35.472  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:35.473  5855  5855 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:35.473  5855  5855 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:35.473  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 12:29:35.473  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:35.473  5855  5855 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:35.473  5855  5855 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:35.473  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:29:35.473  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 12:29:35.474  5855  5855 V BluetoothAdapterState: isTurningOff()=false
11-03 12:29:35.474  5855  5855 V BluetoothAdapterState: isTurningOn()=true
11-03 12:29:35.474  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 12:29:35.474  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:29:35.475  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-03 12:29:35.475  5855  5867 D BluetoothAdapterProperties: ScanMode =  20
11-03 12:29:35.475  5855  5867 D BluetoothAdapterProperties: State =  11
11-03 12:29:35.475  5855  5867 D BluetoothAdapterProperties: Setting state to 12
11-03 12:29:35.475  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-03 12:29:35.477  5855  5867 I BluetoothAdapterState: Entering OnState
,11-03 12:29:35.477  5756  5767 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 12:29:35.478  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 12:29:35.478  5855  5871 D BluetoothAdapterProperties: Scan Mode:21
11-03 12:29:35.479  5855  5871 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 12:29:35.479   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:29:35.480  3174  4019 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 12:29:35.481  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:35.481  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:35.481  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:35.481  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:35.481  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:35.481  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:35.481  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:35.481  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:35.482   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 12:29:35.483   932   932 D BluetoothA2dp: Proxy object connected
,11-03 12:29:35.483  5756  5767 D BluetoothPan: onBluetoothStateChange on: true
11-03 12:29:35.483  3174  3174 D BluetoothInputDevice: Proxy object connected
11-03 12:29:35.483  3174  3174 D HidProfile: Bluetooth service connected
11-03 12:29:35.484  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:35.485  3174  3189 D BluetoothPan: onBluetoothStateChange on: true
11-03 12:29:35.486  5855  5855 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 12:29:35.486  5855  5855 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 12:29:35.486   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:29:35.486  3174  3174 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 12:29:35.486  3174  3174 D PanProfile: Bluetooth service connected
11-03 12:29:35.487  3174  4019 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 12:29:35.487  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:35.487  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:35.487  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:35.487  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:35.487  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:35.487  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:35.487  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:35.487  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:35.488  5855  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:29:35.488  5756  5756 D BluetoothA2dp: Proxy object connected
11-03 12:29:35.488  3174  3174 D BluetoothA2dp: Proxy object connected
11-03 12:29:35.489  5756  5767 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:29:35.489  3174  3189 D BluetoothMap: onBluetoothStateChange: up=true
11-03 12:29:35.490   932  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-03 12:29:35.490  5855  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:29:35.490  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:35.490   932  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-03 12:29:35.491   932  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 12:29:35.491  3174  3187 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 12:29:35.492  5855  5855 D ObexServerSockets: Succeed to create listening sockets 
11-03 12:29:35.492  5855  5855 D ObexServerSockets0: startAccept()
11-03 12:29:35.492  5855  5855 D ObexServerSockets0: prepareForNewConnect()
11-03 12:29:35.492  5756  5756 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 12:29:35.492  5756  5756 D PanProfile: Bluetooth service connected
11-03 12:29:35.493  3770  3798 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:29:35.494  5756  5766 D BluetoothMap: onBluetoothStateChange: up=true
11-03 12:29:35.495  5855  5855 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 12:29:35.495  5855  5855 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 12:29:35.495  5855  5893 D ObexServerSockets0: Accepting socket connection...
,11-03 12:29:35.495  5855  5894 D ObexServerSockets0: Accepting socket connection...
11-03 12:29:35.496  3174  3174 D BluetoothMap: Proxy object connected
11-03 12:29:35.496  3174  3174 D MapProfile: Bluetooth service connected
11-03 12:29:35.496  3174  3174 D BluetoothMap: getConnectedDevices()
,11-03 12:29:35.498  5756  5767 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-03 12:29:35.499   932  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
11-03 12:29:35.500  5756  5766 D BluetoothPbap: onBluetoothStateChange: up=true
,11-03 12:29:35.501  3174  4020 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 12:29:35.501   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:29:35.502  5756  5756 D BluetoothMap: Proxy object connected
11-03 12:29:35.502  5756  5756 D MapProfile: Bluetooth service connected
11-03 12:29:35.502  5756  5756 D BluetoothMap: getConnectedDevices()
11-03 12:29:35.502   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 12:29:35.502   932   932 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
11-03 12:29:35.503  5855  5855 D BluetoothMapService: onReceive
11-03 12:29:35.503  5855  5855 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 12:29:35.503  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 12:29:35.503  5855  5855 D BluetoothMapService: STATE_ON
11-03 12:29:35.504  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:29:35.506  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:35.506  5855  5896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:29:35.506  5756  5756 D BluetoothInputDevice: Proxy object connected
11-03 12:29:35.507  5756  5756 D HidProfile: Bluetooth service connected
11-03 12:29:35.509  5855  5896 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 12:29:35.509  5855  5896 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-03 12:29:35.512  5756  5756 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 12:29:35.518  3607  3607 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 12:29:35.519  5756  5756 D DockEventReceiver: finishStartingService: stopping service
,11-03 12:29:35.524  3174  3174 D BluetoothPbap: Proxy object connected
11-03 12:29:35.524  3174  3174 D PbapServerProfile: Bluetooth service connected
11-03 12:29:35.526  5756  5756 D BluetoothPbap: Proxy object connected
11-03 12:29:35.526  5756  5756 D PbapServerProfile: Bluetooth service connected
,11-03 12:29:35.529   932  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 12:29:35.530  5855  5855 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-03 12:29:35.531  5855  5855 D ObexServerSockets0: prepareForNewConnect()
11-03 12:29:35.535  5752  5752 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
11-03 12:29:35.535  5855  5900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:29:35.548  5855  5904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:29:35.549  5855  5904 I BtOppRfcommListener: Accept thread started.
,11-03 12:29:35.958  5752  5752 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 12:29:35.979  5640  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:35.979  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:35.979  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:35.979  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:35.979  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:35.979  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:35.979  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:35.979  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:35.985  5640  5711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:35.988  5640  5687 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-03 12:29:35.991  5752  5752 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 12:29:35.991  5752  5752 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
11-03 12:29:35.992   932   943 D WifiService: setWifiEnabled: false pid=5640, uid=10077
,11-03 12:29:35.992   932   943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-03 12:29:35.994  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:36.002   932  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 12:29:36.003   932  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 12:29:36.003   932  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 12:29:36.019   932  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 12:29:36.029   509   925 D CommandListener: Setting iface cfg
,11-03 12:29:36.034   932  2981 D WifiStateMachine: Start Dhcp Watchdog 2
,11-03 12:29:36.037   932  2981 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{1}, ntable=[]
,11-03 12:29:36.037   932  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 12:29:36.038   932  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 12:29:36.046   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-03 12:29:36.055   932   932 D RttService: SCAN_AVAILABLE : 1
,11-03 12:29:36.056   932  3102 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 12:29:36.058   932  5909 D DhcpClient: Receive thread started
,11-03 12:29:36.058   932  5909 D DhcpClient: Receive thread stopped
,11-03 12:29:36.059   932  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
,11-03 12:29:36.059   932  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 0
,11-03 12:29:36.063   932  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 12:29:36.064   932  2996 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-03 12:29:36.064   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-03 12:29:36.067   932  2981 D DhcpClient: doQuit
,11-03 12:29:36.067   932  2981 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 12:29:36.068  5752  5752 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-03 12:29:36.069   932  2981 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-03 12:29:36.075   932  5908 D DhcpClient: onQuitting
,11-03 12:29:36.076  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:36.076  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:36.076  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:36.076  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:29:36.076  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:36.076  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:36.076  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:36.076  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:36.078  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:36.079  5752  5752 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 12:29:36.083  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:36.083  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:36.083  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:36.083  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:29:36.083  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:36.083  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:36.083  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:36.083  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:36.084  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:36.088  5752  5752 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 12:29:36.096  5752  5752 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 12:29:36.111  5752  5752 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 12:29:36.216   932  2981 D wifi    : In wifi stop Hal
,11-03 12:29:36.216   932  2981 D wifi    : halHandle = 0x7f71620e00, mVM = 0x7f8dc0d140, mCls = 0x101576
11-03 12:29:36.217   932  5751 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 12:29:36.217   932  5751 D WifiHAL : Got a signal to exit!!!
11-03 12:29:36.217   932  5751 I WifiHAL : Exit wifi_event_loop
11-03 12:29:36.218   932  2981 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-03 12:29:36.218   932  2981 E WifiHAL : Event processing terminated
11-03 12:29:36.218   932  2981 D wifi    : In wifi cleaned up handler
11-03 12:29:36.218   932  2981 I WifiHAL : Internal cleanup completed
11-03 12:29:36.218  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 12:29:36.223  4086  4252 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 12:29:36.224  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:36.227  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:36.243   932  5751 D wifi    : set interface wlan0 flags (DOWN)
,11-03 12:29:36.244   932  2981 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 12:29:36.450   932   949 D Tethering: InitialState.processMessage what=4
,11-03 12:29:36.457   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 12:29:36.502  5640  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:36.502  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:36.502  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:36.502  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:29:36.502  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:36.502  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:36.502  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:36.502  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:36.507  5640  5711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:36.510   932   943 D WifiService: setWifiEnabled: true pid=5640, uid=10077
11-03 12:29:36.510   932   943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-03 12:29:36.511  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:36.518   509   925 D SoftapController: Softap fwReload - Ok
,11-03 12:29:36.522   509   925 D CommandListener: Setting iface cfg
,11-03 12:29:36.523   509   925 D CommandListener: Trying to bring down wlan0
,11-03 12:29:36.524   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-03 12:29:36.529   932  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 12:29:37.015   932  3185 D WifiService: setWifiEnabled: true pid=5640, uid=10077
11-03 12:29:37.019   932  3185 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:29:37.130   932  2981 D wifi    : set interface wlan0 flags (UP)
,11-03 12:29:37.130   932  2981 I WifiHAL : Initializing wifi
,11-03 12:29:37.130   932  2981 I WifiHAL : Creating socket
,11-03 12:29:37.135   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-03 12:29:37.139   932  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-03 12:29:37.139   932  2981 D wifi    : Did set static halHandle = 0x7f71620e00
11-03 12:29:37.140   932  2981 D wifi    : halHandle = 0x7f71620e00, mVM = 0x7f8dc0d140, mCls = 0x1272
11-03 12:29:37.140   932  2981 D wifi    : array field set
,11-03 12:29:37.140   932  2981 I WifiNative-HAL: interface[0] = wlan0
11-03 12:29:37.142   932  5912 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547363098112
11-03 12:29:37.142   932  5912 D wifi    : waitForHalEvents called, vm = 0x7f8dc0d140, obj = 0x1272, env = 0x7f73993300
11-03 12:29:37.144   932  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 12:29:37.146   932  2981 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-03 12:29:37.151  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:37.155  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:37.203  5913  5913 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 12:29:37.273  5913  5913 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 12:29:37.282  5913  5913 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 12:29:37.282  5913  5913 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 12:29:37.522   932  3186 D WifiService: setWifiEnabled: true pid=5640, uid=10077
,11-03 12:29:37.522   932  3186 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:29:38.026   932  3787 D WifiService: setWifiEnabled: true pid=5640, uid=10077
,11-03 12:29:38.026   932  3787 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:29:38.163   932  2981 D WifiConfigStore: Loading config and enabling all networks 
,11-03 12:29:38.173  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:38.173  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:38.173  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:38.173  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:38.173  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:38.173  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:38.173  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:38.173  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:38.178  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:38.185  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:38.185  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:38.185  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:38.185  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:38.185  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:38.185  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:38.185  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:38.185  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:29:38.189  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:38.207   932  2981 D WifiConfigStore: loaded 0 passpoint configs
,11-03 12:29:38.209   932  2981 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 12:29:38.210   932  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-03 12:29:38.211   932  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-03 12:29:38.212   932  2981 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-03 12:29:38.214   932  2981 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-03 12:29:38.215   932  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-03 12:29:38.216   932  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 12:29:38.216   932  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 12:29:38.216   932  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-03 12:29:38.216   932  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-03 12:29:38.216   932  2981 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 12:29:38.217   932  2981 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 12:29:38.237   932  2981 D WifiNative-HAL: Setting external_sim to 1
,11-03 12:29:38.237  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 12:29:38.238   932  2981 D wifi    : setting dfs flag to true, 0x7f7715c9a0
,11-03 12:29:38.239   932  2981 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 12:29:38.239   932  2981 D wifi    : setting scan oui 0x7f7715c9a0
11-03 12:29:38.239   932  2981 D WifiHAL : Sending mac address OUI
,11-03 12:29:38.245   932  2981 E native  : do suspend false
,11-03 12:29:38.255   932  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-03 12:29:38.255   509   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-03 12:29:38.256   932   932 D RttService: SCAN_AVAILABLE : 3
,11-03 12:29:38.256   932  3102 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-03 12:29:38.257   509   925 D CommandListener: Setting iface cfg
,11-03 12:29:38.261   932  2977 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
11-03 12:29:38.261   932  2977 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 12:29:38.272   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=112551 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=11 mControllerEnergyUsed=41 }
,11-03 12:29:38.272   932  2977 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 12:29:38.273   932  2977 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 12:29:38.537  5640  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:38.537  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:38.537  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:38.537  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:38.537  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:38.537  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:38.537  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:38.537  5640  5711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:38.542  5640  5711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:29:38.546  5640  5687 D BluetoothAdapter: enable(): BT is already enabled..!
11-03 12:29:38.547   932  3868 D WifiService: setWifiEnabled: true pid=5640, uid=10077
11-03 12:29:38.547   932  3868 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:29:38.548  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 12:29:38.548  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 12:29:38.548  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 12:29:38.549  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 12:29:38.549  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 12:29:38.549  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6fa14f removed from the list
11-03 12:29:38.549  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 12:29:38.549  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7f0dc removed from the list
,11-03 12:29:38.549  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-03 12:29:38.550  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 12:29:38.550  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 12:29:38.554  5640  5687 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-03 12:29:38.557  5640  5687 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-03 12:29:38.559  5640  5687 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-03 12:29:38.561  5640  5687 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-03 12:29:38.564  5640  5687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-03 12:29:38.565  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-03 12:29:38.566  5640  5687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-03 12:29:38.566  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-03 12:29:38.567  5640  5687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-03 12:29:38.571  5640  5687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-03 12:29:38.571  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3d485d2 Bundle[{}]
11-03 12:29:38.572  5640  5687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-03 12:29:38.572  5640  5687 I io.jxcore.node.LifeCycleMonitor: start: OK
11-03 12:29:38.572  5640  5687 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-03 12:29:38.573  5640  5687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-03 12:29:38.573  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-03 12:29:38.573  5640  5687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-03 12:29:38.573  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-03 12:29:38.574  5640  5687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-03 12:29:38.574  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-03 12:29:38.575  5640  5687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-03 12:29:38.576  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-03 12:29:38.579  5640  5687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-03 12:29:38.581  5640  5687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
11-03 12:29:38.582  5640  5687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-03 12:29:38.583  5640  5687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-03 12:29:38.584  5640  5687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-03 12:29:38.585  5640  5687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-03 12:29:38.587  5640  5687 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-03 12:29:38.589  5640  5687 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-03 12:29:38.589  5640  5687 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-03 12:29:38.591  5640  5687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-03 12:29:38.592  5640  5687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-03 12:29:38.593  5640  5687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-03 12:29:38.593  5640  5687 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 146)
11-03 12:29:38.594  5640  5687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-03 12:29:38.594  5640  5687 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-03 12:29:38.594  5640  5687 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 147)
,11-03 12:29:38.595  5640  5687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-03 12:29:38.597  5640  5687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-03 12:29:38.598  5640  5687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-03 12:29:38.599  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 12:29:38.599  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af036b added. We now have 3 listener(s)
,11-03 12:29:38.601  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 12:29:38.601  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 12:29:38.602  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 12:29:38.602  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 12:29:38.602  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1513ec8 added. We now have 3 listener(s)
11-03 12:29:38.602  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 12:29:38.603  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 12:29:38.607  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 12:29:38.611  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:29:38.611  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:38.611  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:38.611  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:38.611  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:38.611  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:29:38.611  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:29:38.611  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:29:38.613  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:29:38.613  5640  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 12:29:38.616  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:38.617  5640  5687 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-03 12:29:38.617  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:29:38.618  5640  5687 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,11-03 12:29:38.618  5640  5687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,11-03 12:29:38.618  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,11-03 12:29:38.618  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-03 12:29:38.618  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-03 12:29:38.618  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-03 12:29:38.619  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:29:38.620  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-03 12:29:38.620  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 12:29:38.621  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 12:29:38.621  5640  5915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-03 12:29:38.621  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 12:29:38.621  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 12:29:38.621  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-03 12:29:38.621  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-03 12:29:38.621  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:29:38.621  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 12:29:38.622  5640  5915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:29:38.622  5892  5892 W Binder_5: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[34990]" dev="sockfs" ino=34990 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 12:29:38.625  5640  5915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-03 12:29:38.622  5892  5892 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34990]" dev="sockfs" ino=34990 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 12:29:38.627  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 12:29:38.627  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:29:38.627  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 12:29:38.631  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 12:29:38.632  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-03 12:29:38.632  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 12:29:38.634  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.634  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:29:38.634  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 12:29:38.634  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-03 12:29:38.634  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:29:38.635  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.635  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.635  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.635  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:38.636  5640  5687 D BluetoothAdapter: STATE_ON
,11-03 12:29:38.639  5855  5866 D BtGatt.GattService: registerClient() - UUID=926a92e5-2a7e-495e-bc09-98668caba43f
,11-03 12:29:38.640  5855  5871 D BtGatt.GattService: onClientRegistered() - UUID=926a92e5-2a7e-495e-bc09-98668caba43f, clientIf=5
11-03 12:29:38.640  5640  5679 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-03 12:29:38.642  5855  5874 D BtGatt.AdvertiseManager: message : 0
,11-03 12:29:38.644  5855  5874 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:29:38.653  5855  5871 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:29:38.658  5855  5871 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:29:38.658  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.658  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:38.658  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:29:38.659  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.659  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.659  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.659  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.659  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.659  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-03 12:29:38.660  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:29:38.660  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:38.661  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.662  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:38.662  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:38.662  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-03 12:29:38.662  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:29:38.662  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:38.662  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-03 12:29:38.662  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:29:38.662  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:38.662  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:29:38.662  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:29:38.662  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:29:38.662  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:29:38.663  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-03 12:29:38.663  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-03 12:29:38.663  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 12:29:38.665  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 12:29:38.665  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-03 12:29:38.665  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:29:38.665  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:29:38.665  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:29:38.665  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:38.665  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-03 12:29:39.166  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-03 12:29:39.166  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-03 12:29:39.167  5640  5640 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 12:29:39.714   570   570 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-03 12:29:39.714   570   570 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 12:29:41.294  5913  5913 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 12:29:41.299  5913  5913 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 12:29:41.303  5913  5913 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 12:29:41.308  5913  5913 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 12:29:41.335  5913  5913 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 12:29:41.379   932  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 12:29:41.382   932  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-03 12:29:41.383   932  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 12:29:41.397   932  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 12:29:41.432   932  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 12:29:41.779  5913  5913 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 12:29:41.812  5913  5913 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 12:29:41.813  5913  5913 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 12:29:41.821   932  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-03 12:29:41.821   932  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 12:29:41.821   932  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 12:29:41.838   932  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 12:29:41.851   509   925 D CommandListener: Setting iface cfg
,11-03 12:29:41.856   932  2981 D WifiStateMachine: Start Dhcp Watchdog 3
,11-03 12:29:41.862   932  5920 D DhcpClient: Receive thread started
,11-03 12:29:41.868   932  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-03 12:29:41.868   932  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-03 12:29:41.868   932  2996 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-03 12:29:41.949   932  2981 E native  : do suspend false
,11-03 12:29:41.959   932  5919 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 12:29:41.979   932  5920 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172724, domain null
,11-03 12:29:41.979   932  5919 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172724 seconds
,11-03 12:29:41.981   932  5919 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 12:29:41.995   932  5920 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 12:29:41.996   932  5919 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-03 12:29:41.998   509   925 D CommandListener: Setting iface cfg
11-03 12:29:42.003   932  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 12:29:42.009   932  5919 D DhcpClient: Scheduling renewal in 86399s
,11-03 12:29:42.025   932  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-03 12:29:42.027   932  2981 D WifiConfigStore: No blacklist allowed without epno enabled
11-03 12:29:42.028   932  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-03 12:29:42.030   932  2996 D ConnectivityService: Adding iface wlan0 to network 102
,11-03 12:29:42.044   932  2981 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-03 12:29:42.085   932  2996 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-03 12:29:42.085   932  2996 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-03 12:29:42.087   932  2996 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-03 12:29:42.088   932  2996 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-03 12:29:42.090   932  2996 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-03 12:29:42.097   932  2996 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-03 12:29:42.102   932  2996 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-03 12:29:42.102   932  2996 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-03 12:29:42.102   932  2996 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-03 12:29:42.102   932  2981 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-03 12:29:42.102   932  2996 D ConnectivityService:    accepting network in place of null
11-03 12:29:42.102   932  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 12:29:42.103   932  2996 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 12:29:42.114   932  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=116393, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 12:29:42.127   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 12:29:42.148   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 12:29:42.153   932  2996 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-03 12:29:42.153   932  2996 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 12:29:42.153  3747  3902 W QCNEJ   : |CORE| network available: 102
,11-03 12:29:42.154   932  2996 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-03 12:29:42.157   932   949 D Tethering: MasterInitialState.processMessage what=3
11-03 12:29:42.157  3747  3902 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-03 12:29:42.159  3747  3902 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-03 12:29:42.159  3747  3902 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-03 12:29:42.162  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:42.162  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:42.162  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:42.162  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:42.162  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:42.162  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:42.162  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:29:42.162  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 12:29:42.164  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-03 12:29:42.164  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 12:29:42.164  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 12:29:42.164  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 12:29:42.164  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-03 12:29:42.165  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 12:29:42.165  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-03 12:29:42.165  5640  5915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 12:29:42.165  5640  5915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 12:29:42.166  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 12:29:42.166  5640  5915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 12:29:42.166  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 12:29:42.166  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 12:29:42.166  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 12:29:42.166  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 12:29:42.166  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 12:29:42.166  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.166  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.167  5640  5687 D BluetoothAdapter: STATE_ON
,11-03 12:29:42.167  5640  5687 D BluetoothLeScanner: could not find callback wrapper
11-03 12:29:42.167  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 12:29:42.167  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.167  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.167  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-03 12:29:42.167  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.168  5855  5874 D BtGatt.AdvertiseManager: message : 1
11-03 12:29:42.168  5855  5874 D BtGatt.AdvertiseManager: stop advertise for client 5
11-03 12:29:42.169  3998  3998 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-03 12:29:42.170  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:42.170  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:42.170  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:42.170  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:42.170  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:42.170  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:42.170  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:29:42.170  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 12:29:42.171  3865  3865 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 12:29:42.172  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 12:29:42.175  3865  3865 D SystemUpdateService: onCreate
,11-03 12:29:42.179  3865  3865 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-03 12:29:42.179  5855  5871 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-03 12:29:42.180  5855  5871 D BtGatt.GattService: Client app is not null!
11-03 12:29:42.180  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:29:42.180  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:29:42.180  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:29:42.180  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:29:42.180  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:29:42.180  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:42.180  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:29:42.180  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 12:29:42.181  5855  5892 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 12:29:42.181  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 12:29:42.181  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.181  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-03 12:29:42.181  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.181   932  5917 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
11-03 12:29:42.181  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.181  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.181  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 12:29:42.182  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:29:42.182  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.182  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:42.182  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-03 12:29:42.182  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.182  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 12:29:42.182  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 12:29:42.182  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 12:29:42.182  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 12:29:42.185  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.185  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:29:42.185  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.185  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.185  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:42.185  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.185  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.185  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 12:29:42.185  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 12:29:42.186  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 12:29:42.186  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.187  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.188  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.188  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.188  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 12:29:42.188  5640  5640 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-03 12:29:42.188  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:29:42.188  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:29:42.188  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 12:29:42.194  5640  5687 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-03 12:29:42.194  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 12:29:42.195  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 12:29:42.195  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 12:29:42.195  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 12:29:42.195  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:29:42.195  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 12:29:42.197  3865  3865 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-03 12:29:42.198  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:29:42.198  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:29:42.198  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 12:29:42.201  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 12:29:42.201  3865  4336 I iu.UploadsManager: num queued entries: 0
11-03 12:29:42.202  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:29:42.202  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 12:29:42.202  3865  4336 I iu.UploadsManager: num updated entries: 0
11-03 12:29:42.202  3865  4336 I iu.SyncManager: NEXT; no task
,11-03 12:29:42.205  3865  5930 I SystemUpdateService: active receiver: enabled
,11-03 12:29:42.206  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:42.206  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 12:29:42.206  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 12:29:42.206  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 12:29:42.207  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 12:29:42.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:42.208  3865  3865 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-03 12:29:42.208  5640  5687 D BluetoothAdapter: STATE_ON
11-03 12:29:42.209  3865  3865 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 12:29:42.211  5446  5446 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 12:29:42.211  5855  5891 D BtGatt.GattService: registerClient() - UUID=1130e50b-2798-4f6c-b9d0-cd8e354da892
11-03 12:29:42.212  5855  5871 D BtGatt.GattService: onClientRegistered() - UUID=1130e50b-2798-4f6c-b9d0-cd8e354da892, clientIf=5
11-03 12:29:42.212  5640  5679 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 12:29:42.213  5855  5892 D BtGatt.GattService: start scan with filters
,11-03 12:29:42.215  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 12:29:42.215  5446  5446 D SprintDMHelper: simOperator: 
,11-03 12:29:42.215  5446  5446 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-03 12:29:42.216  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.216  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 12:29:42.216  5855  5875 D BtGatt.ScanManager: handling starting scan
11-03 12:29:42.216  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.216  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.216  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 12:29:42.216  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:29:42.216  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.216  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.216  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 12:29:42.216  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.218  5855  5875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec58107
,11-03 12:29:42.219  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.219  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 12:29:42.219  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.219  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.219  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.219  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 12:29:42.219  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 12:29:42.220  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:29:42.220  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:42.221  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:42.221  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:42.221  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:42.226   932  5917 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 11:29:42 GMT], X-Android-Received-Millis=[1478172582224], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478172582204]}
,11-03 12:29:42.226   932  2996 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-03 12:29:42.227   932  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-03 12:29:42.227   932  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-03 12:29:42.228   932  2996 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-03 12:29:42.228  5855  5871 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 12:29:42.229  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 12:29:42.229  5855  5875 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 12:29:42.235  5855  5871 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-03 12:29:42.235  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 12:29:42.235  5855  5875 D BtGatt.ScanManager: Starting BLE batch scan
11-03 12:29:42.235  5855  5875 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 12:29:42.236  3865  5930 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 12:29:42.247  5855  5871 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 12:29:42.247  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 12:29:42.252  3865  5930 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-03 12:29:42.252  3865  5930 I SystemUpdateService: now status is 0 (complete)
11-03 12:29:42.252  3865  5930 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 12:29:42.252  3865  5930 I SystemUpdateService: file has been verified
11-03 12:29:42.252  3865  5930 I SystemUpdateService: OTA package size = 21989297
11-03 12:29:42.253  5855  5871 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 12:29:42.253  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 12:29:42.257  3865  5930 I SystemUpdateService: showing system update notification
,11-03 12:29:42.266   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 12:29:42.267  3865  3865 D SystemUpdateService: onDestroy
,11-03 12:29:42.719  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-03 12:29:42.720  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 12:29:42.720  5640  5640 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 12:29:42.897  5855  5855 D BtGatt.ScanManager: awakened up at time 117176
,11-03 12:29:42.900  5855  5875 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 12:29:42.918  5855  5871 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,11-03 12:29:42.918  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 12:29:42.918  5855  5871 D BtGatt.GattService: current time is 117197511260
11-03 12:29:42.918  5855  5871 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 12:29:42.919  5855  5871 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 12:29:42.923  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
,11-03 12:29:42.923  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-03 12:29:42.923  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-75, mTimestampNanos=117097861675}
,11-03 12:29:43.154   932  2996 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-03 12:29:44.715   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:45.224  5640  5687 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-03 12:29:45.225  5640  5687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-03 12:29:45.225  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,11-03 12:29:45.225  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-03 12:29:45.225  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-03 12:29:45.225  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-03 12:29:45.225  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-03 12:29:45.225  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-03 12:29:45.225  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-03 12:29:45.225  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-03 12:29:45.225  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-03 12:29:45.225  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,11-03 12:29:45.226  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 12:29:45.226  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-03 12:29:45.230  5640  5687 D BluetoothAdapter: STATE_ON
,11-03 12:29:45.237  5855  5865 D BtGatt.GattService: stopScan() - queue size =1
,11-03 12:29:45.242  5855  5872 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 12:29:45.242  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 12:29:45.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 12:29:45.243  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 12:29:45.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.243  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-03 12:29:45.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 12:29:45.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 12:29:45.243  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 12:29:45.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:45.244  5640  5687 D BluetoothAdapter: STATE_ON
11-03 12:29:45.246  5855  5855 D BtGatt.ScanManager: awakened up at time 119525
11-03 12:29:45.249  5855  5892 D BtGatt.GattService: registerClient() - UUID=dd1bd8e5-34a6-456f-b90f-d0e6c7fd3c08
11-03 12:29:45.249  5855  5871 D BtGatt.GattService: onClientRegistered() - UUID=dd1bd8e5-34a6-456f-b90f-d0e6c7fd3c08, clientIf=5
11-03 12:29:45.249  5640  5650 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 12:29:45.250  5855  5865 D BtGatt.GattService: start scan with filters
11-03 12:29:45.251  5855  5871 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 12:29:45.251  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 12:29:45.251  5855  5875 D BtGatt.ScanManager: stopping BLe Batch
,11-03 12:29:45.255  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 12:29:45.255  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.255  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-03 12:29:45.256  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.256  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.256  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-03 12:29:45.256  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 12:29:45.256  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.256  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:45.257  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-03 12:29:45.257  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-03 12:29:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-03 12:29:45.257  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:29:45.258  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-03 12:29:45.259  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 12:29:45.259  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 12:29:45.259  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 12:29:45.259  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 12:29:45.259  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-03 12:29:45.259  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-03 12:29:45.260  5640  5939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 12:29:45.260  5855  5871 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 12:29:45.260  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 12:29:45.261  5855  5875 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 12:29:45.261  5640  5939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:29:45.261  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:29:45.261  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:29:45.259  5872  5872 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32282]" dev="sockfs" ino=32282 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 12:29:45.259  5872  5872 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[32282]" dev="sockfs" ino=32282 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 12:29:45.269  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:45.269  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.269  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:29:45.269  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:29:45.270  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-03 12:29:45.270  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:29:45.270  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.270  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.270  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.270  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:45.271  5640  5687 D BluetoothAdapter: STATE_ON
,11-03 12:29:45.274  5855  5891 D BtGatt.GattService: registerClient() - UUID=1640b0e0-2ce2-4536-a83e-b08872ddd8a2
,11-03 12:29:45.274  5855  5871 D BtGatt.GattService: onClientRegistered() - UUID=1640b0e0-2ce2-4536-a83e-b08872ddd8a2, clientIf=6
,11-03 12:29:45.274  5855  5871 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-03 12:29:45.274  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 12:29:45.274  5640  5679 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-03 12:29:45.274  5855  5871 D BtGatt.GattService: current time is 119554108253
11-03 12:29:45.275  5855  5871 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -84, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
11-03 12:29:45.275  5855  5871 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-03 12:29:45.275  5855  5874 D BtGatt.AdvertiseManager: message : 0
11-03 12:29:45.276  5855  5875 D BtGatt.ScanManager: handling starting scan
,11-03 12:29:45.277  5855  5874 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:29:45.283  5855  5871 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-03 12:29:45.283  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 12:29:45.283  5855  5875 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 12:29:45.292  5855  5871 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-03 12:29:45.297  5855  5871 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 12:29:45.297  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 12:29:45.298  5855  5875 D BtGatt.ScanManager: Starting BLE batch scan
11-03 12:29:45.298  5855  5875 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 12:29:45.303  5855  5871 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-03 12:29:45.303  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.303  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.303  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:29:45.303  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.303  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.304  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.304  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.304  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.304  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.304  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.305  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.305  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-03 12:29:45.305  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-03 12:29:45.305  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 12:29:45.306  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:29:45.306  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.308  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.309  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.309  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:45.309  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-03 12:29:45.309  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:29:45.309  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:45.309  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-03 12:29:45.309  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,m,ain], id: 1
11-03 12:29:45.309  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:45.310  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:29:45.310  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-03 12:29:45.310  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 12:29:45.310  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:29:45.310  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-03 12:29:45.310  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-03 12:29:45.310  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 12:29:45.313  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:29:45.313  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-03 12:29:45.313  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-03 12:29:45.313  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:29:45.313  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:29:45.313  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:29:45.313  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-03 12:29:45.313  5855  5871 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 12:29:45.313  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 12:29:45.318  5855  5871 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-03 12:29:45.318  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 12:29:45.716   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:45.814  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-03 12:29:45.815  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-03 12:29:45.815  5640  5640 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 12:29:46.616   932  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 10 -> obsolete
,11-03 12:29:46.717   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:47.384   932  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 10 -> obsolete
,11-03 12:29:47.718   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:47.901   932  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-03 12:29:48.313  5640  5687 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-03 12:29:48.313  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 12:29:48.313  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 12:29:48.314  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 12:29:48.314  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 12:29:48.315  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-03 12:29:48.315  5640  5939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 12:29:48.315  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 12:29:48.315  5640  5939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 12:29:48.315  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 12:29:48.315  5640  5939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 12:29:48.315  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-03 12:29:48.316  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 12:29:48.316  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af036b removed from the list
11-03 12:29:48.316  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 12:29:48.316  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 12:29:48.316  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 12:29:48.316  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 12:29:48.316  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 12:29:48.316  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 12:29:48.317  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.317  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.317  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-03 12:29:48.320  5640  5687 D BluetoothAdapter: STATE_ON
11-03 12:29:48.322  5855  5891 D BtGatt.GattService: stopScan() - queue size =1
11-03 12:29:48.325  5855  5866 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 12:29:48.326  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-03 12:29:48.326  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.327  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 12:29:48.327  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.327  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.328  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:29:48.328  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-03 12:29:48.328  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.328  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:48.328  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-03 12:29:48.328  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:48.332  5855  5855 D BtGatt.ScanManager: awakened up at time 122611
11-03 12:29:48.332  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:48.333  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-03 12:29:48.333  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.333  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.333  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.333  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.333  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-03 12:29:48.333  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.334  5855  5874 D BtGatt.AdvertiseManager: message : 1
,11-03 12:29:48.335  5855  5871 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 12:29:48.335  5855  5874 D BtGatt.AdvertiseManager: stop advertise for client 6
11-03 12:29:48.335  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 12:29:48.335  5855  5875 D BtGatt.ScanManager: stopping BLe Batch
,11-03 12:29:48.342  5855  5871 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 12:29:48.342  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 12:29:48.343  5855  5875 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 12:29:48.349  5855  5871 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-03 12:29:48.349  5855  5871 D BtGatt.GattService: Client app is not null!
,11-03 12:29:48.349  5855  5891 D BtGatt.GattService: unregisterClient() - clientIf=6
11-03 12:29:48.350  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 12:29:48.350  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.350  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-03 12:29:48.350  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:48.350  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.350  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:48.351  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 12:29:48.351  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-03 12:29:48.351  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.351  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:48.351  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-03 12:29:48.351  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.353  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.353  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 12:29:48.353  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.353  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:48.353  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.353  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:48.353  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.353  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 12:29:48.353  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 12:29:48.355  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 12:29:48.355  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.356  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.356  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-03 12:29:48.357  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
,11-03 12:29:48.357  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1513ec8 removed from the list
11-03 12:29:48.357  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-03 12:29:48.357  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 12:29:48.357  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:29:48.357  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:29:48.357  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-03 12:29:48.357  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:29:48.359  5640  5687 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,11-03 12:29:48.359  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-03 12:29:48.359  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-03 12:29:48.359  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-03 12:29:48.359  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 12:29:48.359  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-03 12:29:48.359  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 12:29:48.360  5640  5687 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-03 12:29:48.361  5640  5687 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,11-03 12:29:48.362  5640  5687 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-03 12:29:48.362  5640  5687 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-03 12:29:48.363  5640  5687 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-03 12:29:48.364  5640  5687 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-03 12:29:48.364  5640  5687 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-03 12:29:48.365  5640  5687 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-03 12:29:48.376  5855  5871 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 12:29:48.376  5855  5871 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 12:29:48.376  5855  5871 D BtGatt.GattService: current time is 122655481481
11-03 12:29:48.376  5855  5871 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -85, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -86, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 12:29:48.376  5855  5871 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 12:29:48.376  5855  5871 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 12:29:48.377  5855  5871 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
11-03 12:29:48.377  5855  5871 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 12:29:48.377  5855  5871 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 12:29:48.719   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:48.858  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 12:29:49.720   570   570 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 12:29:50.105   932  2996 D ConnectivityService: handlePromptUnvalidated 102
,11-03 12:29:50.368  5640  5687 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-03 12:29:50.488  5640  5941 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 12:29:50.488  5640  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 12:29:50.917   932  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-03 12:29:51.283  5640  5941 W !!      : call onHalfStreamCopied
,11-03 12:29:51.283  5640  5941 I testCopyDataAndClose: closing input stream
,11-03 12:29:52.065  5640  5941 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 12:29:52.065  5640  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 12:29:52.066  5640  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 12:29:52.066  5640  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 12:29:52.066  5640  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 12:29:52.066  5640  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-03 12:29:52.066  5640  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 12:29:52.066  5640  5941 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 12:29:52.066  5640  5941 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 12:29:52.066  5640  5941 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 12:29:52.066  5640  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 12:29:53.276   932  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,11-03 12:29:54.721   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:55.722   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:56.545  5640  5687 I StreamCopyingThreadTest: Starting test: testRun
,11-03 12:29:56.551  5640  5942 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:29:56.551  5640  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 12:29:56.723   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:57.725   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:58.726   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:29:59.727   570   570 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 12:30:01.559  5640  5943 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-03 12:30:01.561  5640  5687 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-03 12:30:01.675  5640  5944 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 12:30:01.675  5640  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 12:30:02.113  5640  5649 I art     : Background sticky concurrent mark sweep GC freed 41(36KB) AllocSpace objects, 8(4MB) LOS objects, 5% free, 52MB/55MB, paused 5.191ms total 46.905ms
,11-03 12:30:02.774  3684  3851 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-03 12:30:02.774  3684  3851 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-03 12:30:02.812  3607  3607 I ConfigService: onCreate
,11-03 12:30:03.344  5640  5944 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 12:30:03.344  5640  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 12:30:03.344  5640  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 12:30:03.344  5640  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 12:30:03.344  5640  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 12:30:03.344  5640  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-03 12:30:03.344  5640  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 12:30:03.344  5640  5944 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 12:30:03.344  5640  5944 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-03 12:30:03.345  5640  5944 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 12:30:03.345  5640  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 12:30:07.713  5640  5687 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-03 12:30:07.716  5640  5946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:30:07.716  5640  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 12:30:07.716  5640  5946 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:30:07.716  5640  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 12:30:07.716  5640  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 12:30:07.716  5640  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 12:30:07.717  5640  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-03 12:30:07.717  5640  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 12:30:07.717  5640  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 12:30:07.717  5640  5946 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 12:30:07.717  5640  5946 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-03 12:30:07.717  5640  5946 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:30:07.717  5640  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-03 12:30:07.720  5640  5687 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-03 12:30:07.720  5640  5687 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-03 12:30:07.721  5640  5687 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-03 12:30:07.723  5640  5947 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:30:07.723  5640  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 12:30:07.724  5640  5947 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 172, thread name: My test thread name): Test exception.
,11-03 12:30:07.724  5640  5947 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 172, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:30:07.724  5640  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-03 12:30:07.725  5640  5947 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-03 12:30:07.725  5640  5947 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:30:07.725  5640  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-03 12:30:07.726  5640  5687 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-03 12:30:07.727  5640  5687 E com.test.thalitest.ThaliTestRunner: 
11-03 12:30:07.727  5640  5687 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-03 12:30:07.727  5640  5687 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:30:07.728  5640,  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-03 12:30:07.728  5640  5687 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-03 12:30:07.729  5640  5687 E com.test.t,halitest.ThaliTestRunner: Expected: is <true>
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363,)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:30:07.729  5640  5687 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-03 12:30:07.732  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG UnitTest_app: 'Running unit tests'
11-03 12:30:07.732  5640  5687 I jxcore-log: 
11-03 12:30:07.732  5640  5687 I jxcore-log: *Native tests were executed*
11-03 12:30:07.732  5640  5687 I jxcore-log: 
11-03 12:30:07.732  5640  5687 I jxcore-log: Total number of executed tests:  82
11-03 12:30:07.732  5640  5687 I jxcore-log: 
11-03 12:30:07.732  5640  5687 I jxcore-log: Number of passed tests:  80
11-03 12:30:07.732  5640  5687 I jxcore-log: 
11-03 12:30:07.732  5640  5687 I jxcore-log: Number of failed tests:  2
11-03 12:30:07.732  5640  5687 I jxcore-log: 
11-03 12:30:07.732  5640  5687 I jxcore-log: Number of ignored tests:  0
11-03 12:30:07.732  5640  5687 I jxcore-log: 
11-03 12:30:07.733  5640  5687 I jxcore-log: Total duration:  43756
11-03 12:30:07.733  5640  5687 I jxcore-log: 
11-03 12:30:07.733  5640  5687 I jxcore-log: Failed to execute UT.
11-03 12:30:07.733  5640  5687 I jxcore-log: 
11-03 12:30:07.734  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-03 12:30:07.734  5640  5687 I jxcore-log: 
11-03 12:30:07.735  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG UnitTest_ap,p: 'Unit Test app is loaded'
11-03 12:30:07.735  5640  5687 I jxcore-log: 
11-03 12:30:07.738  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:30:07.738  5640  5687 I jxcore-log: 
11-03 12:30:07.738  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.738  5640  5687 I jxcore-log: 
11-03 12:30:07.739  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:30:07.739  5640  5687 I jxcore-log: 
11-03 12:30:07.740  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.740  5640  5687 I jxcore-log: 
11-03 12:30:07.740  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:30:07.740  5640  5687 I jxcore-log: 
11-03 12:30:07.741  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.741  5640  5687 I jxcore-log: 
11-03 12:30:07.741  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-03 12:30:07.741  5640  5687 I jxcore-log: 
,11-03 12:30:07.741  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-03 12:30:07.741  5640  5687 I jxcore-log: 
11-03 12:30:07.742  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-03 12:30:07.742  5640  5687 I jxcore-log: 
11-03 12:30:07.742  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 12:30:07.742  5640  5687 I jxcore-log: 
11-03 12:30:07.742  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:30:07.742  5640  5687 I jxcore-log: 
,11-03 12:30:07.742  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.742  5640  5687 I jxcore-log: 
11-03 12:30:07.743  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.743  5640  5687 I jxcore-log: 
11-03 12:30:07.743  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.743  5640  5687 I jxcore-log: 
11-03 12:30:07.743  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.743  5640  5687 I jxcore-log: 
,11-03 12:30:07.743  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.743  5640  5687 I jxcore-log: 
11-03 12:30:07.743  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.743  5640  5687 I jxcore-log: 
11-03 12:30:07.744  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.744  5640  5687 I jxcore-log: 
11-03 12:30:07.744  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:30:07.744  5640  5687 I jxcore-log: 
,11-03 12:30:07.744  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.744  5640  5687 I jxcore-log: 
11-03 12:30:07.744  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:30:07.744  5640  5687 I jxcore-log: 
11-03 12:30:07.744  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.744  5640  5687 I jxcore-log: 
11-03 12:30:07.745  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:30:07.745  5640  5687 I jxcore-log: 
11-03 12:30:07.745  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.745  5640  5687 I jxcore-log: 
,11-03 12:30:07.745  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 12:30:07.745  5640  5687 I jxcore-log: 
11-03 12:30:07.746  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.746  5640  5687 I jxcore-log: 
11-03 12:30:07.746  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.746  5640  5687 I jxcore-log: 
11-03 12:30:07.746  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.746  5640  5687 I jxcore-log: 
11-03 12:30:07.746  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.746  5640  5687 I jxcore-log: 
,11-03 12:30:07.748  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.748  5640  5687 I jxcore-log: 
11-03 12:30:07.748  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.748  5640  5687 I jxcore-log: 
11-03 12:30:07.748  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.748  5640  5687 I jxcore-log: 
11-03 12:30:07.748  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.748  5640  5687 I jxcore-log: 
11-03 12:30:07.749  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.749  5640  5687 I jxcore-log: 
11-03 12:30:07.749  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.749  5640  5687 I jxcore-log: 
,11-03 12:30:07.749  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.749  5640  5687 I jxcore-log: 
11-03 12:30:07.749  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.749  5640  5687 I jxcore-log: 
11-03 12:30:07.749  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.749  5640  5687 I jxcore-log: 
11-03 12:30:07.749  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.749  5640  5687 I jxcore-log: 
11-03 12:30:07.750  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.750  5640  5687 I jxcore-log: 
11-03 12:30:07.750  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.750  5640  5687 I jxcore-log: 
11-03 12:30:07.750  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.750  5640  5687 I jxcore-log: 
11-03 12:30:07.750  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.750  5640  5687 I jxcore-log: 
11-03 12:30:07.750  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.750  5640  5687 I jxcore-log: 
,11-03 12:30:07.751  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.751  5640  5687 I jxcore-log: 
11-03 12:30:07.751  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.751  5640  5687 I jxcore-log: 
11-03 12:30:07.751  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.751  5640  5687 I jxcore-log: 
11-03 12:30:07.751  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.751  5640  5687 I jxcore-log: 
11-03 12:30:07.751  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.751  5640  5687 I jxcore-log: 
11-03 12:30:07.752  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.752  5640  5687 I jxcore-log: 
11-03 12:30:07.752  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.752  5640  5687 I jxcore-log: 
11-03 12:30:07.752  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.752  5640  5687 I jxcore-log: 
,11-03 12:30:07.752  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.752  5640  5687 I jxcore-log: 
11-03 12:30:07.752  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.752  5640  5687 I jxcore-log: 
11-03 12:30:07.752  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.752  5640  5687 I jxcore-log: 
11-03 12:30:07.753  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:30:07.753  5640  5687 I jxcore-log: 
11-03 12:30:07.753  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.753  5640  5687 I jxcore-log: 
,11-03 12:30:07.753  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:30:07.753  5640  5687 I jxcore-log: 
11-03 12:30:07.753  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.753  5640  5687 I jxcore-log: 
11-03 12:30:07.753  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:30:07.753  5640  5687 I jxcore-log: 
11-03 12:30:07.754  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.754  5640  5687 I jxcore-log: 
11-03 12:30:07.754  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.754  5640  5687 I jxcore-log: 
11-03 12:30:07.754  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.754  5640  5687 I jxcore-log: 
11-03 12:30:07.754  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.754  5640  5687 I jxcore-log: 
11-03 12:30:07.754  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.754  5640  5687 I jxcore-log: 
11-03 12:30:07.754  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.754  5640  5687 I jxcore-log: 
11-03 12:30:07.755  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.755  5640  5687 I jxcore-log: 
11-03 12:30:07.755  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:30:07.755  5640  5687 I jxcore-log: 
11-03 12:30:07.755  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.755  5640  5687 I jxcore-log: 
11-03 12:30:07.755  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-03 12:30:07.755  5640  5687 I jxcore-log: 
,11-03 12:30:07.756  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:30:07.756  5640  5687 I jxcore-log: 
11-03 12:30:07.756  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.756  5640  5687 I jxcore-log: 
11-03 12:30:07.756  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:30:07.756  5640  5687 I jxcore-log: 
11-03 12:30:07.756  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.756  5640  5687 I jxcore-log: 
11-03 12:30:07.756  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:30:07.756  5640  5687 I jxcore-log: 
11-03 12:30:07.756  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:30:07.756  5640  5687 I jxcore-log: 
11-03 12:30:07.757  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 12:30:07.757  5640  5687 I jxcore-log: 
,11-03 12:30:07.757  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-03 12:30:07.757  5640  5687 I jxcore-log: 
11-03 12:30:07.757  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 12:30:07.757  5640  5687 I jxcore-log: 
11-03 12:30:07.760  5640  5640 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-03 12:30:07.762  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-03 12:30:07.762  5640  5687 I jxcore-log: 
,11-03 12:30:07.762  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - WARN testUtils: 'myNameCallback not set!'
11-03 12:30:07.762  5640  5687 I jxcore-log: 
11-03 12:30:07.763  5640  5687 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,11-03 12:30:07.764  5640  5687 I jxcore-log: 2016-11-03 11:30:07 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-03 12:30:07.764  5640  5687 I jxcore-log: 
,11-03 12:30:07.844  3607  3607 I ConfigService: onDestroy
,11-03 12:30:09.728   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:30:09.796  5640  5687 I jxcore-log: 2016-11-03 11:30:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-03 12:30:09.796  5640  5687 I jxcore-log: 
,11-03 12:30:10.131  5640  5687 I jxcore-log: 2016-11-03 11:30:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-03 12:30:10.131  5640  5687 I jxcore-log: 
,11-03 12:30:10.146  5640  5687 I jxcore-log: 2016-11-03 11:30:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-03 12:30:10.146  5640  5687 I jxcore-log: 
,11-03 12:30:10.729   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:30:11.242  5640  5687 I jxcore-log: 2016-11-03 11:30:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-03 12:30:11.242  5640  5687 I jxcore-log: 
,11-03 12:30:11.414  5640  5687 I jxcore-log: 2016-11-03 11:30:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-03 12:30:11.414  5640  5687 I jxcore-log: 
,11-03 12:30:11.419  5640  5687 I jxcore-log: 2016-11-03 11:30:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-03 12:30:11.419  5640  5687 I jxcore-log: 
,11-03 12:30:11.424  5640  5687 I jxcore-log: 2016-11-03 11:30:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-03 12:30:11.424  5640  5687 I jxcore-log: 
,11-03 12:30:11.730   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:30:11.910  5640  5687 I jxcore-log: 2016-11-03 11:30:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-03 12:30:11.910  5640  5687 I jxcore-log: 
,11-03 12:30:11.954  5640  5687 I jxcore-log: 2016-11-03 11:30:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-03 12:30:11.954  5640  5687 I jxcore-log: 
,11-03 12:30:11.968  5640  5687 I jxcore-log: 2016-11-03 11:30:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-03 12:30:11.968  5640  5687 I jxcore-log: 
,11-03 12:30:11.972  5640  5687 I jxcore-log: 2016-11-03 11:30:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-03 12:30:11.972  5640  5687 I jxcore-log: 
,11-03 12:30:12.259  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-03 12:30:12.259  5640  5687 I jxcore-log: 
,11-03 12:30:12.403  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-03 12:30:12.403  5640  5687 I jxcore-log: 
,11-03 12:30:12.731   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:30:12.777  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-03 12:30:12.777  5640  5687 I jxcore-log: 
,11-03 12:30:12.815  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-03 12:30:12.815  5640  5687 I jxcore-log: 
,11-03 12:30:12.822  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-03 12:30:12.822  5640  5687 I jxcore-log: 
,11-03 12:30:12.828  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-03 12:30:12.828  5640  5687 I jxcore-log: 
,11-03 12:30:12.837  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-03 12:30:12.837  5640  5687 I jxcore-log: 
,11-03 12:30:12.851  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-03 12:30:12.851  5640  5687 I jxcore-log: 
,11-03 12:30:12.857  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-03 12:30:12.857  5640  5687 I jxcore-log: 
,11-03 12:30:12.886  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-03 12:30:12.886  5640  5687 I jxcore-log: 
,11-03 12:30:12.924  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-03 12:30:12.924  5640  5687 I jxcore-log: 
,11-03 12:30:12.943  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-03 12:30:12.943  5640  5687 I jxcore-log: 
,11-03 12:30:12.952  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-03 12:30:12.952  5640  5687 I jxcore-log: 
,11-03 12:30:12.973  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-03 12:30:12.973  5640  5687 I jxcore-log: 
,11-03 12:30:12.976  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-03 12:30:12.976  5640  5687 I jxcore-log: 
,11-03 12:30:12.982  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-03 12:30:12.982  5640  5687 I jxcore-log: 
,11-03 12:30:12.986  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-03 12:30:12.986  5640  5687 I jxcore-log: 
,11-03 12:30:12.998  5640  5687 I jxcore-log: 2016-11-03 11:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-03 12:30:12.998  5640  5687 I jxcore-log: 
,11-03 12:30:13.004  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-03 12:30:13.004  5640  5687 I jxcore-log: 
,11-03 12:30:13.024  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-03 12:30:13.024  5640  5687 I jxcore-log: 
,11-03 12:30:13.034  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-03 12:30:13.034  5640  5687 I jxcore-log: 
,11-03 12:30:13.045  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-03 12:30:13.045  5640  5687 I jxcore-log: 
,11-03 12:30:13.054  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-03 12:30:13.054  5640  5687 I jxcore-log: 
,11-03 12:30:13.066  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-03 12:30:13.066  5640  5687 I jxcore-log: 
,11-03 12:30:13.076  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-03 12:30:13.076  5640  5687 I jxcore-log: 
,11-03 12:30:13.082  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-03 12:30:13.082  5640  5687 I jxcore-log: 
,11-03 12:30:13.088  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-03 12:30:13.088  5640  5687 I jxcore-log: 
,11-03 12:30:13.094  5640  5687 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-03 12:30:13.095  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - INFO testUtils: 'BLE multiple advertisement supported'
11-03 12:30:13.095  5640  5687 I jxcore-log: 
,11-03 12:30:13.169  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:13.169  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:13.169  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:13.169  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:13.169  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:13.169  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:13.169  5640  5687 I jxcore-log: 
,11-03 12:30:13.437  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:13.437  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:13.437  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:13.437  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:13.437  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:13.437  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:13.437  5640  5687 I jxcore-log: 
,11-03 12:30:13.441  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:13.441  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:13.441  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:13.441  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:13.441  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:13.441  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:13.441  5640  5687 I jxcore-log: 
,11-03 12:30:13.732   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:30:13.914  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:13.914  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:13.914  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:13.914  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:13.914  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:13.914  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:13.914  5640  5687 I jxcore-log: 
,11-03 12:30:13.917  5640  5687 I jxcore-log: 2016-11-03 11:30:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:13.917  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:13.917  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:13.917  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:13.917  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:13.917  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:13.917  5640  5687 I jxcore-log: 
,11-03 12:30:14.733   570   570 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 12:30:14.949  5640  5687 I jxcore-log: 2016-11-03 11:30:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:14.949  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:14.949  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:14.949  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:14.949  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:14.949  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:14.949  5640  5687 I jxcore-log: 
,11-03 12:30:14.952  5640  5687 I jxcore-log: 2016-11-03 11:30:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:14.952  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:14.952  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:14.952  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:14.952  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:14.952  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:14.952  5640  5687 I jxcore-log: 
,11-03 12:30:15.993  5640  5687 I jxcore-log: 2016-11-03 11:30:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:15.993  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:15.993  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:15.993  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:15.993  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:15.993  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:15.993  5640  5687 I jxcore-log: 
,11-03 12:30:16.002  5640  5687 I jxcore-log: 2016-11-03 11:30:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:16.002  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:16.002  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:16.002  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:16.002  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:16.002  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:16.002  5640  5687 I jxcore-log: 
,11-03 12:30:17.037  5640  5687 I jxcore-log: 2016-11-03 11:30:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:17.037  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:17.037  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:17.037  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:17.037  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:17.037  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:17.037  5640  5687 I jxcore-log: 
,11-03 12:30:17.039  5640  5687 I jxcore-log: 2016-11-03 11:30:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:17.039  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:17.039  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:17.039  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:17.039  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:17.039  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:17.039  5640  5687 I jxcore-log: 
,11-03 12:30:17.566   932   952 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-03 12:30:17.569  3811  3811 W Binder_9: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32825]" dev="sockfs" ino=32825 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:17.577  3684  3684 I Keyboard.Facilitator: onFinishInput()
11-03 12:30:17.572  3811  3811 W Binder_9: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[32825]" dev="sockfs" ino=32825 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:17.591   932   952 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 12:30:17.591   932   952 I Adreno  : Build Date                       : 12/06/15
11-03 12:30:17.591   932   952 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 12:30:17.591   932   952 I Adreno  : Local Branch                     : mybranch17112971
11-03 12:30:17.591   932   952 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 12:30:17.591   932   952 I Adreno  : Remote Branch                    : NONE
11-03 12:30:17.591   932   952 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 12:30:17.630   386  2610 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (194 us)
,11-03 12:30:18.076  5640  5687 I jxcore-log: 2016-11-03 11:30:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:18.076  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:18.076  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:18.076  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:18.076  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:18.076  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:18.076  5640  5687 I jxcore-log: 
,11-03 12:30:18.083  5640  5687 I jxcore-log: 2016-11-03 11:30:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:18.083  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:18.083  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:18.083  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:18.083  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:18.083  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:18.083  5640  5687 I jxcore-log: 
,11-03 12:30:18.319  5640  5640 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-03 12:30:18.319  5640  5640 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-03 12:30:18.353   932   952 I sensors : batch
,11-03 12:30:18.354   932   952 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-03 12:30:18.356  5640  5640 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3d485d2 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7d7490c, 16908290=android.view.AbsSavedState$1@7d7490c}, android:focusedViewId=100}]}]
11-03 12:30:18.356  5640  5640 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-03 12:30:18.357  5640  5640 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-03 12:30:18.357  5640  5640 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-03 12:30:18.359   932   952 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-03 12:30:18.359   932   952 I sensors : activate
11-03 12:30:18.361   932   950 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,11-03 12:30:18.362   386   386 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f966c3c00
11-03 12:30:18.363   386   386 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,11-03 12:30:18.366   932  2786 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-03 12:30:18.367   932  2786 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-03 12:30:18.584   509   925 D TetherController: Setting IP forward enable = 1
,11-03 12:30:18.649   386   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-03 12:30:18.649   386   386 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-03 12:30:18.650   932  3118 D SurfaceControl: Excessive delay in setPowerMode(): 289ms
,11-03 12:30:18.653   932   952 I DreamManagerService: Entering dreamland.
,11-03 12:30:18.654   932   952 I PowerManagerService: Dozing...
,11-03 12:30:18.655   932   947 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-03 12:30:18.676  3756  3756 W Binder_7: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[25329]" dev="sockfs" ino=25329 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 12:30:18.676  3756  3756 W Binder_7: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[25329]" dev="sockfs" ino=25329 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:18.681   932  3185 I sensors : batch
11-03 12:30:18.681   932  3185 I sensors : activate
,11-03 12:30:18.684   932  2786 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-03 12:30:18.687   932  2786 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-03 12:30:18.688   514   514 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-03 12:30:18.692   932  2981 E native  : do suspend false
,11-03 12:30:18.700   932  2981 D WifiConfigStore: No blacklist allowed without epno enabled
,11-03 12:30:18.706  3770  4782 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
11-03 12:30:18.706  3770  4782 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
,11-03 12:30:18.707  3770  4782 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
,11-03 12:30:18.707   527  1479 D         : oem-qmi: Connection accepted
11-03 12:30:18.707   527  1479 D         : oem-qmi: Waiting to accept connection
,11-03 12:30:18.709   932   932 I sensors : activate
11-03 12:30:18.709   514  3028 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
11-03 12:30:18.710  3770  4782 D         : oem_qmi_lib:output 0
11-03 12:30:18.710  3770  4782 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-03 12:30:18.712   932  2981 E native  : do suspend true
11-03 12:30:18.712   932  2786 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-03 12:30:18.727  3770  4782 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-03 12:30:18.727  3770  4782 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-03 12:30:18.727  3770  4782 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-03 12:30:18.727   527  1479 D         : oem-qmi: Connection accepted
11-03 12:30:18.728   527  1479 D         : oem-qmi: Waiting to accept connection
,11-03 12:30:18.730  3770  4782 D         : oem_qmi_lib:output 0
,11-03 12:30:18.730  3770  4782 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-03 12:30:19.115  5640  5687 I jxcore-log: 2016-11-03 11:30:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:19.115  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:19.115  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:19.115  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:19.115  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:19.115  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:19.115  5640  5687 I jxcore-log: 
,11-03 12:30:19.121  5640  5687 I jxcore-log: 2016-11-03 11:30:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:19.121  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:19.121  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:19.121  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:19.121  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:19.121  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:19.121  5640  5687 I jxcore-log: 
,11-03 12:30:19.191   932  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,11-03 12:30:20.160  5640  5687 I jxcore-log: 2016-11-03 11:30:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:20.160  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:20.160  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:20.160  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:20.160  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:20.160  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:20.160  5640  5687 I jxcore-log: 
,11-03 12:30:20.165  5640  5687 I jxcore-log: 2016-11-03 11:30:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:20.165  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:20.165  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:20.165  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:20.165  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:20.165  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:20.165  5640  5687 I jxcore-log: 
,11-03 12:30:20.405   932  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154683, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 12:30:21.200  5640  5687 I jxcore-log: 2016-11-03 11:30:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:21.200  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:21.200  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:21.200  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:21.200  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:21.200  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:21.200  5640  5687 I jxcore-log: 
,11-03 12:30:21.206  5640  5687 I jxcore-log: 2016-11-03 11:30:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:21.206  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:21.206  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:21.206  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:21.206  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:21.206  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:21.206  5640  5687 I jxcore-log: 
,11-03 12:30:22.089   932  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,11-03 12:30:22.279  5640  5687 I jxcore-log: 2016-11-03 11:30:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:22.279  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:22.279  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:22.279  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:22.279  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:22.279  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:22.279  5640  5687 I jxcore-log: 
,11-03 12:30:22.285  5640  5687 I jxcore-log: 2016-11-03 11:30:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:22.285  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:22.285  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:22.285  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:22.285  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:22.285  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:22.285  5640  5687 I jxcore-log: 
,11-03 12:30:22.638  3865  5991 I EventLogService: Aggregate from 1478170810580 (log), 1478170810580 (data)
,11-03 12:30:22.955  4086  4532 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-03 12:30:23.318  5640  5687 I jxcore-log: 2016-11-03 11:30:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:23.318  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:23.318  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:23.318  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:23.318  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:23.318  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:23.318  5640  5687 I jxcore-log: 
,11-03 12:30:23.322  5640  5687 I jxcore-log: 2016-11-03 11:30:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:23.322  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:23.322  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:23.322  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:23.322  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:23.322  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:23.322  5640  5687 I jxcore-log: 
,11-03 12:30:24.352  5640  5687 I jxcore-log: 2016-11-03 11:30:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:24.352  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:24.352  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:24.352  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:24.352  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:24.352  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:24.352  5640  5687 I jxcore-log: 
,11-03 12:30:24.358  5640  5687 I jxcore-log: 2016-11-03 11:30:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:24.358  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:24.358  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:24.358  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:24.358  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:24.358  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:24.358  5640  5687 I jxcore-log: 
,11-03 12:30:25.389  5640  5687 I jxcore-log: 2016-11-03 11:30:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:25.389  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:25.389  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:25.389  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:25.389  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:25.389  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:25.389  5640  5687 I jxcore-log: 
,11-03 12:30:25.394  5640  5687 I jxcore-log: 2016-11-03 11:30:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:25.394  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:25.394  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:25.394  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:25.394  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:25.394  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:25.394  5640  5687 I jxcore-log: 
,11-03 12:30:26.198   932  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=160477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-03 12:30:26.450  5640  5687 I jxcore-log: 2016-11-03 11:30:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:26.450  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:26.450  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:26.450  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:26.450  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:26.450  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:26.450  5640  5687 I jxcore-log: 
,11-03 12:30:26.457  5640  5687 I jxcore-log: 2016-11-03 11:30:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:26.457  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:26.457  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:26.457  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:26.457  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:26.457  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:26.457  5640  5687 I jxcore-log: 
,11-03 12:30:27.484  5640  5687 I jxcore-log: 2016-11-03 11:30:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:30:27.484  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:30:27.484  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:30:27.484  5640  5687 I jxcore-log: emit@events.js:82:1
11-03 12:30:27.484  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:30:27.484  5640  5687 I jxcore-log: emit@events.js:82:1'
11-03 12:30:27.484  5640  5687 I jxcore-log: 
,11-03 12:30:27.495  5640  5687 E jxcore  : Error!: error is undefined
11-03 12:30:27.495  5640  5687 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-03 12:30:27.499  5640  5687 I jxcore-log: 2016-11-03 11:30:27 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-03 12:30:27.499  5640  5687 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-03 12:30:27.499  5640  5687 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-03 12:30:27.499  5640  5687 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-03 12:30:27.499  5640  5687 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-03 12:30:27.499  5640  5687 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-03 12:30:27.499  5640  5687 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-03 12:30:27.499  5640  5687 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-03 12:30:27.500  5640  5687 I jxcore-log: 2016-11-03 11:30:27 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-03 12:30:27.500  5640  5687 I jxcore-log: 
,11-03 12:30:27.503  5640  5687 E jxcore-log: TypeError: 
11-03 12:30:27.503  5640  5687 E jxcore-log: error is undefined
11-03 12:30:27.503  5640  5687 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-03 12:30:27.503  5640  5687 E jxcore-log: 
,11-03 12:30:27.601   932  3817 D GraphicsStats: Buffer count: 2
11-03 12:30:27.601   932  3880 I WindowState: WIN DEATH: Window{1288099 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-03 12:30:27.602   932  2991 D WifiService: Client connection lost with reason: 4
,11-03 12:30:27.611   529   529 I Zygote  : Process 5640 exited cleanly (139)
,11-03 12:30:27.613   932  3450 I ActivityManager: Process com.test.thalitest (pid 5640) has died
,11-03 12:30:27.628   932  3450 I ActivityManager: Start proc 5995:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-03 12:30:27.700  5995  5995 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-03 12:30:27.718  5995  5995 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-03 12:30:27.723  5995  5995 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2001-2002)
,11-03 12:30:27.723  5995  5995 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 12:30:27.732  5995  5995 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a6ebf0f}
,11-03 12:30:27.732  5995  5995 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 12:30:27.732  5995  5995 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 12:30:27.735  5995  5995 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 12:30:27.736  5995  5995 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 12:30:27.746  5995  5995 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 12:30:27.754  5995  5995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 12:30:27.754  5995  5995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 12:30:27.754  5995  5995 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 12:30:27.754  5995  5995 I Adreno  : Build Date                       : 12/06/15
11-03 12:30:27.754  5995  5995 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 12:30:27.754  5995  5995 I Adreno  : Local Branch                     : mybranch17112971
11-03 12:30:27.754  5995  5995 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 12:30:27.754  5995  5995 I Adreno  : Remote Branch                    : NONE
11-03 12:30:27.754  5995  5995 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 12:30:27.786   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bb4439:true
,11-03 12:30:27.799   403   403 W Binder_1: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[15109]" dev="sockfs" ino=15109 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:27.799   403   403 W Binder_1: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[15109]" dev="sockfs" ino=15109 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:27.811  5995  5995 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 12:30:27.819  5995  5995 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 12:30:27.839   403   403 W Binder_1: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[34284]" dev="sockfs" ino=34284 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:27.842  5995  6031 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-03 12:30:27.839   403   403 W Binder_1: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[34284]" dev="sockfs" ino=34284 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:27.842   942   942 W Binder_1: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[15121]" dev="sockfs" ino=15121 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:27.842   942   942 W Binder_1: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[15121]" dev="sockfs" ino=15121 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:27.846  5995  6018 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-03 12:30:27.883  5995  6031 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 12:30:27.889  3449  3449 W Binder_5: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[13821]" dev="sockfs" ino=13821 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:27.893   932  3449 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5640 uid 10077
,11-03 12:30:27.889  3449  3449 W Binder_5: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[13821]" dev="sockfs" ino=13821 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:27.892  3817  3817 W Binder_A: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[13820]" dev="sockfs" ino=13820 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:27.892  3817  3817 W Binder_A: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[13820]" dev="sockfs" ino=13820 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:30:27.895  3684  3684 I Keyboard.Facilitator: onFinishInput()
,11-03 12:30:27.915   932   950 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +267ms (total +300ms)
,11-03 12:30:27.917  5995  5995 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5995
,11-03 12:30:27.978  5995  5995 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 12:30:28.013  5993  5993 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-03 12:30:28.030  5993  5993 D AndroidRuntime: CheckJNI is OFF
,11-03 12:30:28.052  5993  5993 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-03 12:30:28.074  5993  5993 I Radio-JNI: register_android_hardware_Radio DONE
,11-03 12:30:28.088  5993  5993 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-03 12:30:28.094   932   945 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-03 12:30:28.094   932   945 I ActivityManager: Killing 5995:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-03 12:30:28.140   932   943 D GraphicsStats: Buffer count: 2
11-03 12:30:28.140   932  3873 I WindowState: WIN DEATH: Window{3840c5c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-03 12:30:28.193   932   945 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-03 12:30:28.194   932   945 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-03 12:30:28.195   932   945 E ActivityManager: Failure starting process com.test.thalitest
11-03 12:30:28.195   932   945 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-03 12:30:28.195   932   945 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:30:28.195   932   945 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:30:28.195   932   945 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 12:30:28.195   932   945 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-03 12:30:28.195   932   955 I art     : Starting a blocking GC Explicit
,11-03 12:30:28.195   932   945 I ActivityManager:   Force finishing activity ActivityRecord{7691381 u0 com.test.thalitest/.MainActivity t68}
,11-03 12:30:28.202   932  3449 W ActivityManager: Spurious death for ProcessRecord{eac803a 0:com.test.thalitest/u0a77}, curProc for 5995: null
,11-03 12:30:28.276   932   955 I art     : Explicit concurrent mark sweep GC freed 16523(1143KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 1.689ms total 80.611ms
,11-03 12:30:28.299   932   955 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-03 12:30:28.302  5993  5993 I art     : System.exit called, status: 0
11-03 12:30:28.302  5993  5993 I AndroidRuntime: VM exiting with result code 0.
,11-03 12:30:28.307   932   955 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-03 12:30:28.311   932   945 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-03 12:30:28.314  5855  5855 D BluetoothMapAppObserver: onReceive
11-03 12:30:28.314  5855  5855 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-03 12:30:28.320  4086  4187 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-03 12:30:28.331   932  2970 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-03 12:30:28.333  3684  3684 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-03 12:30:28.348  3684  6046 I Keyboard.Facilitator.DecoderInitializer: run()
,11-03 12:30:28.365  3684  6046 I Decoder : createOrResetDecoder
,11-03 12:30:28.379  3434  6049 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-03 12:30:28.399  3770  3770 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-03 12:30:28.401  3607  3607 I ConfigService: onCreate
,11-03 12:30:28.423   932   932 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-03 12:30:28.426    27    27 W kworker/2:1: type=1400 audit(0.0:141): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 12:30:28.432    27    27 W kworker/2:1: type=1400 audit(0.0:142): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 12:30:28.428  3607  3607 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-03 12:30:28.428  3607  3607 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-03 12:30:28.435  3684  6046 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-03 12:30:28.449    27    27 W kworker/2:1: type=1400 audit(0.0:143): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 12:30:28.475  3607  3607 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/ns.db'.
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:30:28.475  3607  3607 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-03 12:30:28.475  3607  3607 D AndroidRuntime: Shutting down VM
11-03 12:30:28.475  3434  6049 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
11-03 12:30:28.476  3607  3607 E AndroidRuntime: FATAL EXCEPTION: main
11-03 12:30:28.476  3607  3607 E AndroidRuntime: Process: com.google.process.gapps, PID: 3607
11-03 12:30:28.476  3607  3607 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:30:28.476  3607  3607 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-03 12:30:28.477  3434  6049 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-03 12:30:28.477  3434  6049 E AndroidRuntime: Process: android.process.acore, PID: 3434
11-03 12:30:28.477  3434  6049 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:30:28.477  3434  6049 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: Can't write: system_app_crash
11-03 12:30:28.482   932  6056 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 12:30:28.482   932  6056 E DropBoxManagerService: 	... 5 more
11-03 12:30:28.482   932  6055 E DropBoxManagerService: Can't write: system_app_crash
11-03 12:30:28.482   932  6055 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-03 12:30:28.482   932  6055 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 12:30:28.482   932  6055 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 12:30:28.482   932  6055 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 12:30:28.482   932  6055 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 12:30:28.482   932  6055 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 12:30:28.482   932  6055 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 12:30:28.482   932  6055 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 12:30:28.482   932  6055 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 12:30:28.482   932  6055 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 12:30:28.482   932  6055 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 12:30:28.482   932  6055 E DropBoxManagerService: 	... 5 more
11-03 12:30:28.483  3607  3607 I Process : Sending signal. PID: 3607 SIG: 9
11-03 12:30:28.498  3865  6054 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-03 12:30:28.498  3865  6054 D AccountUtils: Clearing selected account for com.test.thalitest
11-03 12:30:28.504  3434  6049 I Process : Sending signal. PID: 3434 SIG: 9
11-03 12:30:28.506   932  2991 D WifiService: Client connection lost with reason: 4
11-03 12:30:28.506  3684  3684 W GmsClient: service died
11-03 12:30:28.511   932  3186 I ActivityManager: Process com.google.process.gapps (pid 3607) has died
11-03 12:30:28.512   932  3186 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
11-03 12:30:28.512   932  3186 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 11000ms
11-03 12:30:28.512   932  3186 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
,11-03 12:30:28.512   932  3186 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms

```
