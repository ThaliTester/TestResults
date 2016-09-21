#### Test 856066048ca4f27_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-21 04:30:33.516   930  2972 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-21 04:30:33.977  5881  5881 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 04:30:33.982  5881  5881 D AndroidRuntime: CheckJNI is OFF
09-21 04:30:34.010  5881  5881 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 04:30:34.042  5881  5881 I Radio-JNI: register_android_hardware_Radio DONE
09-21 04:30:34.057  5881  5881 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-21 04:30:34.060   930   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-21 04:30:34.077  5881  5881 D AndroidRuntime: Shutting down VM
09-21 04:30:34.084  3688  3900 W SearchService: Abort, client detached.
09-21 04:30:34.093  3688  5677 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@13d04da
09-21 04:30:34.093  3688  5870 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-21 04:30:34.095  3688  3688 I HotwordDetector: Closing mic
09-21 04:30:34.112   930  3547 I ActivityManager: Start proc 5891:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-21 04:30:34.163   512  5872 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-21 04:30:34.165   512  5872 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
09-21 04:30:34.170   512  5872 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
09-21 04:30:34.170   512  5872 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
09-21 04:30:34.172   512  2991 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-21 04:30:34.178  3688  5869 I MicroRecognitionRnrImpl: Detection finished
09-21 04:30:34.178  3688  5681 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-21 04:30:34.197  5891  5891 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-21 04:30:34.217  5891  5891 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-21 04:30:34.240  5891  5891 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 1770-1789)
09-21 04:30:34.240  5891  5891 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-21 04:30:34.255  5891  5891 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {79f43d4}
09-21 04:30:34.255  5891  5891 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-21 04:30:34.255  5891  5891 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-21 04:30:34.259  5891  5891 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-21 04:30:34.260  5891  5891 E SysUtils: ApplicationContext is null in ApplicationStatus
09-21 04:30:34.289  5891  5891 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-21 04:30:34.298  5891  5891 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 04:30:34.298  5891  5891 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 04:30:34.298  5891  5891 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-21 04:30:34.298  5891  5891 I Adreno  : Build Date                       : 12/06/15
09-21 04:30:34.298  5891  5891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-21 04:30:34.298  5891  5891 I Adreno  : Local Branch                     : mybranch17112971
09-21 04:30:34.298  5891  5891 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-21 04:30:34.298  5891  5891 I Adreno  : Remote Branch                    : NONE
09-21 04:30:34.298  5891  5891 I Adreno  : Reconstruct Branch               : NOTHING
09-21 04:30:34.330   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e941c95:true
09-21 04:30:34.365   405   405 W Binder_2: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[24377]" dev="sockfs" ino=24377 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 04:30:34.365   405   405 W Binder_2: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[24377]" dev="sockfs" ino=24377 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 04:30:34.376  5891  5891 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-21 04:30:34.384  5891  5891 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
09-21 04:30:34.408   728   728 W Binder_3: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[35997]" dev="sockfs" ino=35997 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 04:30:34.408   728   728 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[35997]" dev="sockfs" ino=35997 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 04:30:34.411  5891  5929 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-21 04:30:34.412  3124  3124 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[16223]" dev="sockfs" ino=16223 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 04:30:34.412  3124  3124 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[16223]" dev="sockfs" ino=16223 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 04:30:34.416  5891  5916 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-21 04:30:34.443  5891  5929 I OpenGLRenderer: Initialized EGL, version 1.4
09-21 04:30:34.518   940   940 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[34942]" dev="sockfs" ino=34942 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 04:30:34.522   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +433ms
09-21 04:30:34.518   940   940 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[34942]" dev="sockfs" ino=34942 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 04:30:34.522  3153  3153 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[34941]" dev="sockfs" ino=34941 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 04:30:34.522  3153  3153 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[34941]" dev="sockfs" ino=34941 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 04:30:34.527  3418  3418 I Keyboard.Facilitator: onFinishInput()
09-21 04:30:34.563  5891  5891 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5891
09-21 04:30:34.691  5891  5891 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-21 04:30:34.792  5891  5931 D jxcore_app_log: JniHelper::setJavaVM(0xf50bc000), pthread_self() = -582223568
09-21 04:30:34.795  5891  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 04:30:34.795  5891  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 04:30:34.795  5891  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 04:30:34.795  5891  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 04:30:34.795  5891  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-21 04:30:34.795  5891  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@565f0fb added. We now have 1 listener(s)
09-21 04:30:34.798  5891  5931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-21 04:30:34.798  5891  5931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 04:30:34.799  5891  5931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 04:30:34.799  5891  5931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-21 04:30:34.801  5891  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f9edd56 added. We now have 1 listener(s)
09-21 04:30:34.801  5891  5931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 04:30:34.807   930  2973 D WifiService: New client listening to asynchronous messages
09-21 04:30:34.807  5891  5931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 04:30:34.807  5891  5931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 04:30:34.807  5891  5931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 04:30:34.807  5891  5931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 04:30:34.807  5891  5931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-21 04:30:34.809  5891  5931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 04:30:34.809  5891  5931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
09-21 04:30:34.812  5891  5931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-21 04:30:34.813  5891  5931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 04:30:34.813  5891  5931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 04:30:34.813  5891  5931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 04:30:34.813  5891  5931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 04:30:34.813  5891  5931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 04:30:34.813  5891  5931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 04:30:34.813  5891  5931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 04:30:34.813  5891  5931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 04:30:34.813  5891  5931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 04:30:34.813  5891  5931 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 04:30:34.813  5891  5931 I io.jxcore.node.LifeCycleMonitor: start: OK
09-21 04:30:34.894  5891  5891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 04:30:34.897  5891  5891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 04:30:34.900  5891  5891 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-21 04:30:35.159  5891  5939 W jxcore-log: Initializing JXcore engine
09-21 04:30:35.159  5891  5939 W jxcore-log: JXcore engine is ready
09-21 04:30:35.182  5939  5939 W Thread-58: type=1400 audit(0.0:117): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12682 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-21 04:30:35.182  5939  5939 W Thread-58: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[15370]" dev="sockfs" ino=15370 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-21 04:30:35.182  5939  5939 W Thread-58: type=1400 audit(0.0:119): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 04:30:35.182  5939  5939 W Thread-58: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[35967]" dev="sockfs" ino=35967 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
09-21 04:30:35.191  5891  5939 W jxcore-log: Starting JXcore engine
09-21 04:30:35.242  5891  5939 W jxcore-log: Platform android
09-21 04:30:35.242  5891  5939 W jxcore-log: 
09-21 04:30:35.242  5891  5939 W jxcore-log: Process ARCH arm
09-21 04:30:35.242  5891  5939 W jxcore-log: 
09-21 04:30:35.364  5891  5939 I jxcore-log: JXcore Cordova bridge is ready!
09-21 04:30:35.364  5891  5939 I jxcore-log: 
09-21 04:30:35.364  5891  5939 W jxcore-log: JXcore engine is started
09-21 04:30:35.378  5891  5931 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-21 04:30:35.383  5891  5891 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 04:30:36.549   535   535 I ServiceManager: Waiting for service AtCmdFwd...

```
